###老师打分
<pre>
Post theses/mark.json
</pre>

参数名      |类型及范围      |说明
---    		|---				|---- 
selectionid |int |选题id
titleid |int |论题id
studentid|int |学生id
article_score|String|论文分数
oral_score|String|答辩分数
comment|String |评论



<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": [
        {
            "articleScore": 60,
            "comment": "还需努力",
            "createAt": "2013-03-10T10:24:50",
            "oralScore": 70,
            "selectionid": 1,
            "studentid": 2,
            "titleid": 1
        }
    ]
}

