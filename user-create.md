####创建用户
<pre>
POST user/create.json
</pre>

参数名      |类型及范围    	|说明
---				|---				|---- 
username |String |用户名（学号）
deptid  	|long 			|系id,若传majorid 可不传
 	majorid    |long 			|专业id（高级管理员、管理员、教师可选，学生必选）	
gender    |byte   		|性别，可选，默认0
email    |String     	| 邮箱，可选
level    |level     	|用户类型  必选，只能创建比当前账户低的类型 80 超级管理员70 高级管理员60 管理员40 出题教师30 教师10 学生0 游客
screenname    |String     	|昵称，可选
password   |String   |密码，可选，不传时和username一样


 

 
 
<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
        "avatar": null,
        "avatar_thumb": null,
        "department": 1,
        "email": null,
        "gender": 0,
        "level": 10,
        "major": 1,
        "screenname": "波潮",
        "userid": 11,
        "username": "092011088"
    }
}
</code>
</pre>

