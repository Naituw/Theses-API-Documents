###获取会话信息列表
<pre>
POST　messages/list.json
</pre>

参数名      |类型及范围      |说明
---    		|---				|---- 
conversation_id |int |会话编号
count |int|单次获取的数量
since_id |int|获取大于since_id的消息列表
max_id|int |获取小于max_id的消息列表
count |int|单次获取的数量

<pre>
<code>
{
    "code": 200,
    "message": "成功",
    "object": [
        {
            "content": "test3",
            "conversationId": 9,
            "createAt": "2013-03-22T22:09:03",
            "messageId": 36,
            "userId": 4
        },
        {
            "content": "test2",
            "conversationId": 9,
            "createAt": "2013-03-22T22:13:04",
            "messageId": 37,
            "userId": 4
        },
        {
            "content": "test2",
            "conversationId": 9,
            "createAt": "2013-03-22T22:13:07",
            "messageId": 38,
            "userId": 4
        }
    ]
}
</code>
</pre>


