###批量获取选题
<pre>
Get theses/availables.json 
</pre>
参数名      |类型及范围      |说明
---    		|---				|---- 
page |int |页码
count |int |单页的数量
<pre>
返回结果示例：(测试参数：)
<code>
{
    "code": 200,
    "message": "成功",
    "object": [
        {
            "available_major": [
                "3",
                "2",
                "1"
            ],
            "createAt": "2013-04-08T20:42:06",
            "deptid": 1,
            "description": "测试状态测试状态",
            "require_info": "测试状态测试状态",
            "state": 41,
            "studentNum": 3,
            "students": null,
            "teacher": {
                "avatar": "http://lwapi-pic.stor.sinaapp.com/user_1_22.jpg",
                "avatar_thumb": "http://lwapi-picmin.stor.sinaapp.com/user_1_22.jpg",
                "department": null,
                "email": "245358419@qq.com",
                "gender": 1,
                "level": 40,
                "major_id": 1,
                "screenname": "波潮",
                "userid": 1,
                "username": "bobo"
            },
            "teacherid": 1,
            "title": "测试状态测试状态",
            "titleid": 10
        }
    ]
}
</code>
</pre>

