#### 更新密码


<pre>
POST account/set_password.json
</pre>

参数名      |类型及范围  		|说明   
---				|---				|----
old_password 	|String 			|旧密码，经base64加密过 
password  |String     		|用户密码，格式为 basic：+（账号：密码的base64加密）

返回结果示例：
<code>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
        "compose": 1354182570799,
        "deadline": 1353343603504,
        "oral_examination": 1355071603504,
        "teacher_chosen": 1355021538095,
        "title_assign": 1352886570799,
        "title_chosen": 1353318570799
    }
}
</code>
</pre>
