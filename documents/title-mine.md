### 我的论题
###批量获取用户
<pre>
Get titles/mine.json
</pre>

参数名      |类型及范围      |说明
---    		|---				|---- 
page |int |可选 默认1
count|int |单页获取的数量 默认20


<pre>
返回结果示例1：
<code>
{
    "code": 200,
    "message": "成功",
    "object": [
        {
            "available_major": [
                "1",
                "2",
                "3",
                "5"
            ],
            "createAt": "2013-03-03T10:12:41",
            "deptid": 1,
            "description": "要求有网页、android和ios版",
            "requireInfo": "答辩前完成",
            "state": 1,
            "studentNum": 1,
            "teacherid": 1,
            "title": "基于新浪sae的毕业论文管理系统",
            "titleid": 1
        },
        {
            "available_major": [
                "1",
                "2",
                "3",
                "5"
            ],
            "createAt": "2013-03-03T10:02:03",
            "deptid": 1,
            "description": "要求有网页、android和ios版",
            "requireInfo": "答辩前完成",
            "state": 1,
            "studentNum": 2,
            "teacherid": 1,
            "title": "毕业论文管理系统",
            "titleid": 2
        }
    ]
}
返回示例2：
{
    "code": 200,
    "message": "成功",
    "object": [
        {
            "articleScore": 0,
            "comment": "\"\"",
            "createAt": "2013-03-03T10:12:41",
            "oralScore": 0,
            "selectionid": 1,
            "studentid": 2,
            "titleid": 1
        }
    ]
}

