###获取论题附加信息
<pre>
GET title/extra_info.json
</pre>

参数名      |类型及范围      |说明
---    		|---				|---- 
titleid |int |论题id


<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
        "student": [
            {
                "avatar": null,
                "avatar_thumb": null,
                "department": {
                    "deptid": 1,
                    "directorid": 1,
                    "majors": null,
                    "name": "电软系",
                    "schoolname": "中山大学南方学院"
                },
                "email": null,
                "gender": 1,
                "level": 60,
                "major_id": 0,
                "screenname": "电软系测试",
                "userid": 13,
                "username": "dzx"
            }
        ],
        "teacher": {
            "avatar": "http://lwapi-pic.stor.sinaapp.com/user_1_27.jpg",
            "avatar_thumb": "http://lwapi-picmin.stor.sinaapp.com/user_1_27.jpg",
            "department": null,
            "email": "245358419@qq.com",
            "gender": 1,
            "level": 30,
            "major_id": 1,
            "screenname": "波潮",
            "userid": 1,
            "username": "bobo"
        }
    }
}

