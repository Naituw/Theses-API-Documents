###获取私信列表
<pre>
Get conversations/list.json
</pre>




<pre>
返回结果示例一：
<code>
{
    "code": 200,
    "message": "成功",
    "object": []
}

</pre>

</code>

<pre>
返回结果示例二：（basic:Ym9ibzoxMjM0）
<code>
{
    "code": 200,
    "message": "成功",
    "object": [
        {
            "conversationid": 8,
            "create_at": 1363961308000,
            "last_update": 1363961939000,
            "last_user_id": 2,
            "userA": 1,
            "userB": 2,
            "with_user": {
                "avatar": "http://lwapi-pic.stor.sinaapp.com/user_2_48.png",
                "avatar_thumb": "http://lwapi-picmin.stor.sinaapp.com/user_2_48.png",
                "department": {
                    "deptid": 1,
                    "directorid": 1,
                    "majors": null,
                    "name": "电软系",
                    "schoolname": "中山大学南方学院"
                },
                "email": "naituw@gmail.com",
                "gender": 1,
                "level": 10,
                "major_id": 1,
                "screenname": "吴天",
                "userid": 2,
                "username": "092011070"
            }
        },
        {
            "conversationid": 9,
            "create_at": 1363961343000,
            "last_update": 1363961343000,
            "last_user_id": 1,
            "userA": 1,
            "userB": 4,
            "with_user": {
                "avatar": "http://lwapi-pic.stor.sinaapp.com/user_2_48.png",
                "avatar_thumb": "http://lwapi-picmin.stor.sinaapp.com/user_2_48.png",
                "department": {
                    "deptid": 1,
                    "directorid": 1,
                    "majors": null,
                    "name": "电软系",
                    "schoolname": "中山大学南方学院"
                },
                "email": "naituw@gmail.com",
                "gender": 1,
                "level": 10,
                "major_id": 1,
                "screenname": "吴天",
                "userid": 2,
                "username": "092011070"
            }
        }
    ]
}

</pre>

</code>