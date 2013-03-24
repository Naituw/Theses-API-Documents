###发送私信
<pre>
POST message/create.json
</pre>

参数名      |类型及范围      |说明
---    		|---				|---- 
to_user_id |int |接收者编号
content |String |内容



<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
        "content": "testMe",
        "conversationId": 6,
        "createAt": "2013-03-18T23:43:16",
        "messageId": 8,
        "userId": 8
    }
}
</code>
</pre>

