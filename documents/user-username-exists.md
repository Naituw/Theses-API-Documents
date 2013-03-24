###判断用户是否存在
<pre>
POST user/username_exists.json
</pre>

参数名      |类型及范围      |说明
---				|---				|---- 
username |String |用户名


<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
        "result": 1
    }
}
</code>
</pre>

