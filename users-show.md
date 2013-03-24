###批量获取用户
<pre>
Get users/show.json
</pre>

参数名      |类型及范围      |说明
---  			|---				|---- 
majorid |int |专业编号
deptid |int |系别编号（与majorid二选一）
max_level |int |最大权限 可选，level小于或等于这个值的
min_level |int |最小权限 可选，level大于或等于这个值的
level |int |权限（与max_level，min_level三选一）可选，只显示当前level的，不受minlevel、maxlevel 影响
page |int |可选 默认1
count |int|单页获取的数量 


<pre>
返回结果示例：(测试参数：deptid=1&max_level=30)
<code>
{
    "code": 200,
    "message": "成功",
    "object": [
        {
            "avatar": "http://lwapi-pic.stor.sinaapp.com/user_2_8.png",
            "avatar_thumb": "http://lwapi-picmin.stor.sinaapp.com/user_2_8.png",
            "department": null,
            "email": "naituw@gmail.com",
            "gender": 1,
            "level": 10,
            "major_id": 1,
            "screenname": "吴天",
            "userid": 2,
            "username": "092011070"
        },
        {
            "avatar": "http://null-pic.stor.sinaapp.com/user_1_40.png",
            "avatar_thumb": "http://null-picmin.stor.sinaapp.com/user_1_40.png",
            "department": null,
            "email": "",
            "gender": 0,
            "level": 30,
            "major_id": 1,
            "screenname": "",
            "userid": 4,
            "username": "bobo1"
        },
        {
            "avatar": null,
            "avatar_thumb": null,
            "department": null,
            "email": null,
            "gender": 0,
            "level": 10,
            "major_id": 1,
            "screenname": "波潮",
            "userid": 11,
            "username": "092011088"
        },
        {
            "avatar": null,
            "avatar_thumb": null,
            "department": null,
            "email": null,
            "gender": 2,
            "level": 30,
            "major_id": 0,
            "screenname": "教师测试",
            "userid": 12,
            "username": "teacher"
        }
    ]
}

