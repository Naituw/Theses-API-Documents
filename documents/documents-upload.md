###批量获取用户
<pre>
Post documents/upload.json
</pre>

参数名      |类型及范围      |说明
---    		|---				|---- 
titleid |int |学生的论题id
upload |File |文件



<pre>
返回结果示例：(注：文件上传仅支持doc和docx类型)
<code>
{
    "code": 200,
    "message": "成功",
    "object": {
        "authorid": 2,
        "createAt": "2013-03-08T22:24:54",
        "docid": 2,
        "doctype": 0,
        "fileurl": "http://lwapi-document.stor.sinaapp.com/document_092011070.doc",
        "titleid": 12
    }
}
