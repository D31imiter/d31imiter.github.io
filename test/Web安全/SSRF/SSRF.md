#### 漏洞成因

服务端提供了从其他服务器应用获取数据的功能且没有对目标地址做过滤与限制

##### 可利用的协议

file：协议结合目录遍历读取任意文件

gopher： 协议打开端口

dict： 协议主要用于结合 curl 攻击

dict： 协议主要用于结合 curl 攻击

##### 相关函数

1. `file_get_contents()`：函数从用户指定的url获取内容，然后指定一个文件名j进行保存，并展示给用户。file_put_content函数把一个字符串写入文件中。
2. `curl_exec`：函数用于执行指定的cURL会话
