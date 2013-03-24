####创建论文题目
<pre>
POST theses/create_title.json
</pre>

参数名      |类型及范围      |说明
---				|---				|---- 
title |String |论文题目
student_num  	|int 			|可选该论文的学生数量
available_majors    |String     	| 逗号分隔id
description    |String     	|描述
require_info   |String   |要求
 
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
        ],
        "createAt": "2013-01-06T20:49:01",
        "deptid": 1,
        "description": "要求有网页、android和ios版",
        "requireInfo": "答辩前完成",
        "state": 0,
        "studentNum": 2,
        "teacherid": 1,
        "title": "基于新浪sae的毕业论文管理系统",
        "titleid": 1
    }
}
</code>
</pre>

