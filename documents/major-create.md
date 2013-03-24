####创建专业

<pre>
POST major/create.json
</pre>

参数名      |类型及范围    	|说明
---				|---				|---- 
name  	|String 			|专业名称
deptid    |long 			|所属系别的id（可选，不选默认为管理员所在的系别）
<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
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
                    "majorid": 4,
                    "name": "信息工程"
                }
            ],
            "name": "电软系",
            "schoolname": "中山大学南方学院"
        },
        "deptid": 1,
        "majorid": 4,
        "name": "信息工程"
    }
}
</code>
</pre>