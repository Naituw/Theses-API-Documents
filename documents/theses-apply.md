###批量获取用户
<pre>
POST theses/apply.json
</pre>

参数名      |类型及范围      |说明
---    		|---				|---- 
teacherid |int |老师的编号
title |String |论文题目
description |String | 论文描述


<pre>
返回结果示例：
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
        "available_major": [
            "1"
        ],
        "createAt": "2013-03-08T00:19:12",
        "deptid": 1,
        "description": "基于android的记账本",
        "requireInfo": "",
        "state": 0,
        "studentNum": 1,
        "teacherid": 8,
        "title": "记账本",
        "titleid": 7
    }
}
</code>
</pre>

