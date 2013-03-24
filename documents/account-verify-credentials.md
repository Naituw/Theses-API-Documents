####登陆验证

<pre>
POST account/verify_credentials.json
</pre>

参数名      |类型及范围     |说明
---				|---				|----
Auth 	|String 			|加密后的数据

<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
        "avatar": "http://lwapi-pic.stor.sinaapp.com/user_1_27.jpg",
        "avatar_thumb": "http://lwapi-picmin.stor.sinaapp.com/user_1_27.jpg",
        "department": {
            "deptid": 1,
            "directorid": 1,
            "majors": [
                {
                    "department": null,
                    "deptid": 1,
                    "majorid": 1,
                    "name": "计算机科学与技术"
                },
                {
                    "department": null,
                    "deptid": 1,
                    "majorid": 2,
                    "name": "软件工程"
                },
                {
                    "department": null,
                    "deptid": 1,
                    "majorid": 3,
                    "name": "通讯工程"
                },
                {
                    "department": null,
                    "deptid": 1,
                    "majorid": 8,
                    "name": "信息工程"
                }
            ],
            "name": "电软系",
            "schoolname": "中山大学南方学院"
        },
        "email": "245358419@qq.com",
        "gender": 1,
        "level": 30,
        "major_id": 1,
        "screenname": "波潮",
        "userid": 1,
        "username": "bobo"
    }
}
</code>
</pre>