####取消某个老师的出题老师资格


<pre>
POST teachers/leveldown.json
</pre>

参数名      |类型及范围      |说明
---  			|---				|---- 
id  	|String 			|老师id，可一次性传多个id，用','隔开


 
 
<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": [
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

