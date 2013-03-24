#### 获取和设置 开始给教师添加资格的日期、开始出题的日期、开始选题的日期、选题结束的日期、论文撰写结束的日期、答辩的日期

<pre>
GET/POST theses/times.json
</pre>

参数名      |类型及范围  		|说明
---				|---				|---- 
teacher_chosen  	|long 			|开始给教师添加资格的日期
 	title_assign    |long 			|开始出题的日期	
title_chosen    |long   		|开始选题的日期
compose    |long     	| 选题结束的日期 （开始撰写）
deadline    |long     	|论文撰写结束的日期	
oral_examination    |long     	|答辩的日期	


 

 
 
<pre>
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