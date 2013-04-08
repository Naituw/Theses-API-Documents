###批量获取选题
<pre>
Get theses/availables.json 
</pre>
参数名      |类型及范围      |说明
---    		|---				|---- 
page |int |页码
count |int |单页的数量
<pre>
返回结果示例：(测试参数：)
<code>
{
    "code": 200,
    "message": "成功",
    "object": [
        {
            "available_major": [
                "3",
                "2",
                "1"
            ],
            "createAt": "2013-04-08T20:42:06",
            "deptid": 1,
            "description": "测试状态测试状态",
            "require_info": "测试状态测试状态",
            "state": 41,
            "studentNum": 3,
            "students": null,
            "teacher": null,
            "teacherid": 1,
            "title": "测试状态测试状态",
            "titleid": 10
        }
    ]
}
</code>
</pre>

