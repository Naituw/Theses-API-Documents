#### 手动验证邮箱


<pre>
GET account/verify_email.json
</pre>


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
        "email_verified": 0,
        "gender": 1,
        "last_email_sent": 1367592027000,
        "level": 40,
        "major_id": 1,
        "screenname": "波潮",
        "userid": 1,
        "username": "bobo"
    }
}
</code>
</pre>
