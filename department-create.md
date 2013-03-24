####创建系别

<pre>
POST department/create.json
</pre>

参数名      |类型及范围    	|说明
---				|---				|---- 
name  	|String 			|系的名称
directorid   |long 			|开始出题的日期	



 

 
 
<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
        "deptid": 6,
        "directorid": 8,
        "majors": [],
        "name": "经管系",
        "schoolname": "中山大学南方学院"
    }
}
</code>
</pre>