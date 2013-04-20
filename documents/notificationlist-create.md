###发送通知
<pre>
POST  notification/create.json
</pre>

参数名      |类型及范围      |说明
---  			|---				|---- 
title |String |标题
content|String |内容
url |String |链接



<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
        "content": "内容测试",
        "createAt": "2013-03-27T00:04:04",
        "deptid": 1,
        "notificationid": 6,
        "title": "标题测试",
        "url": "https://github.com/Naituw/Theses-API-Documents/blob/master/README.md"
    }
}

</code>
</pre>
