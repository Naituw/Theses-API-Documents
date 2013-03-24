#### 获取某个系的老师
<pre>
GET teacher/show.json
</pre>
参数名      |类型及范围    	|说明
---				|---				|---- 
depart_id  	|int 			|系别编号
<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": [
        {
            "avatar": null,
            "avatar_thumb": null,
            "department": 1,
            "email": null,
            "gender": 1,
            "level": 40,
            "major": 1,
            "screenname": "波潮",
            "userid": 9,
            "username": "092011062"
        },
        {
            "avatar": "http://null-pic.stor.sinaapp.com/user_1_40.png",
            "avatar_thumb": "http://null-picmin.stor.sinaapp.com/user_1_40.png",
            "department": 1,
            "email": "",
            "gender": 0,
            "level": 30,
            "major": 1,
            "screenname": "",
            "userid": 4,
            "username": "bobo1"
        },
        {
            "avatar": null,
            "avatar_thumb": null,
            "department": 1,
            "email": null,
            "gender": 2,
            "level": 30,
            "major": 0,
            "screenname": "教师测试",
            "userid": 12,
            "username": "teacher"
        }
    ]
}
</code>
</pre>
