# Ajax-Encapsulation
This function is Encapsulation of Ajax.It support optional method of ‘get’ or ‘post’，and temporarily support Content-Type of 'application/x-www-form-urlencoded' when type is 'post'.
You can use ajax(opts) like this:

	  ajax({
		  url: '/login',   //接口地址
		  type: 'post',    // 类型， post 或者 get,
		  data: {
			  "username":"limian",
			  "password": "1234"
		  },
		  success: function (ret) {
			  alert(ret);       
		  },
		  error: function () {
			  alert('出错了')
		  }
	  })

