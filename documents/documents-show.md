###获取某个学生的文档
<pre>
Get theses/documents.json
</pre>

参数名      |类型及范围      |说明
---    		|---				|---- 
titleid |int |论题id
authorid |int |上传者id 学生可选 默认1



<pre>
接口限制：
如果当前用户是学生，则titleid必须是自己当前论题的ID
如果是出题教师，则titleid的teacherid必须是自己
如果是管理员、高级管理员，则titleid必须是当前系的
</pre>
<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": [
        {
            "author": {
                "avatar": "http://lwapi-pic.stor.sinaapp.com/user_2_28.png",
                "avatar_thumb": "http://lwapi-picmin.stor.sinaapp.com/user_2_28.png",
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
            },
            "authorid": 2,
            "createAt": "2013-03-08T22:24:26",
            "docid": 1,
            "doctype": 0,
            "fileurl": "http://lwapi-document.stor.sinaapp.com/document_092011070.doc",
            "titleid": 12
        }
    ]
}
    



