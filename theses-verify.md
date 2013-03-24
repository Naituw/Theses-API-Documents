####审核题目
<pre>
GET theses/verify.json
</pre>

参数名      |类型及范围      |说明
---				|---				|---- 
title |int |论文id
pass|int|通过与否（1通过，2未通过）


<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
        "available_major": [
            "1",
            "2",
            "3",
            "5"
        ],
        "createAt": "2013-01-06T21:01:28",
        "deptid": 1,
        "description": "要求有网页、android和ios版",
        "requireInfo": "答辩前完成",
        "state": 1,
        "studentNum": 2,
        "teacherid": 1,
        "title": "基于新浪sae的毕业论文管理系统",
        "titleid": 1
    }
}
</code>
</pre>

