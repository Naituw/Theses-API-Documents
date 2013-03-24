#### 获取某个系别的专业详细信息

<pre>
GET majors/show.json?department_id=1
</pre>

参数名      |类型及范围			|说明
---				|---				|----
department_id 	|String 			|系别ID
 		
<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
        "deptid": 1,
        "directorid": 1,
        "majors": [
            {
                "deptid": 1,
                "majorid": 1,
                "name": "计算机科学与技术"
            }
        ],
        "name": "电软系",
        "schoolname": "中山大学南方学院"
    }
}
</code>
</pre>