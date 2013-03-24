#### 更新用户

<pre>
POST account/update_profile.json
</pre>

参数名      |类型及范围   	|说明
---				|---				|----
Auth 	|String 			|加密后的数据
screenname  |String 			|用户名
gender  |Byte 			|用户性别，1男生，2女生
email  |String 			|邮箱


 		
<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
        "avatar": null,
        "avatar_thumb": null,
        "department": 0,
        "email": "gybciy1s1s@sina.com",
        "gender": 1,
        "level": 100,
        "major": 1,
        "screenname": "一波潮水",
        "userid": 1,
        "username": "bobo"
    }

}
</code>
</pre>