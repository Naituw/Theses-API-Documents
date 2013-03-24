#### 更新头像


<pre>
POST account/update_avatar.json
</pre>

参数名      |类型及范围  		|说明   
---				|---				|----
upload 	|File 			|文件

<code>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
        "avatar": "http://lwapi-pic.stor.sinaapp.com/user_1_22.jpg",
        "avatar_thumb": "http://lwapi-picmin.stor.sinaapp.com/user_1_22.jpg",
        "department": {
            "deptid": 1,
            "directorid": 1,
            "majors": null,
            "name": "电软系",
            "schoolname": "中山大学南方学院"
        },
        "email": "245358419@qq.com",
        "gender": 1,
        "level": 40,
        "major_id": 1,
        "screenname": "波潮",
        "userid": 1,
        "username": "bobo"
    }
}
</code>
</pre>
