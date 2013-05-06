###获取通知
<pre>
Get notifications/list.json
</pre>

参数名      |类型及范围      |说明
---  			|---				|---- 
page |int |页码，默认1
count |int |每页的数量，默认20



<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": [
        {
            "content": "内容测试",
            "createAt": "2013-03-26T22:52:14",
            "deptid": 1,
            "notificationid": 1,
            "title": "标题测试",
            "url": ""
        },
        {
            "content": "内容测试2",
            "createAt": "2013-03-26T22:52:22",
            "deptid": 1,
            "notificationid": 2,
            "title": "标题测试1",
            "url": ""
        },
        {
            "content": "内容测试2",
            "createAt": "2013-03-26T22:52:28",
            "deptid": 1,
            "notificationid": 3,
            "title": "标题测试2",
            "url": ""
        },
        {
            "content": "内容测试2",
            "createAt": "2013-03-26T22:52:30",
            "deptid": 1,
            "notificationid": 4,
            "title": "标题测试3",
            "url": ""
        },
        {
            "content": "内容测试2",
            "createAt": "2013-03-26T22:52:43",
            "deptid": 1,
            "notificationid": 5,
            "title": "标题测试",
            "url": "https://github.com/Naituw/Theses-API-Documents/blob/master/README.md"
        }
    ]
}

</code>
</pre>
