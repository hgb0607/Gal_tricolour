# Gal_tricolour
三色绘恋手机补丁

1.新建一个文本文档patch.tjs
2.复制下面代码到文件中
3.将patch.tsj放到steam游戏《三色绘恋》根目录下
4.用吉里吉里2模拟器打开即可



代码内容
---
```
class HttpRequest
{
function HttpRequest() {}
function open() {}
function setRequestHeader() {}
function send() {}
function sendStorage() {}
function abort() {}
function getAllResponseHeaders() {return %[];}
function getResponseHeader() {return "";}
function getResponseText() {return "";}
var readyState = 0;
var response = "";
var responseData = <% 00 %>;
var status = 404;
var statusText = "Not Found";
var contentType = "text/html";
var contentTypeEncoding = "utf-8";
var contentLength = 0;
function onReadyStateChange() {}
function onProgress() {}
function finalize() {}
};
with(HttpRequest)
{
.UNINITIALIZED = 0;
.OPEN = 1; 
.SENT = 2; 
.RECEIVING = 3; 
.LOADED = 4; 
}
Plugins.link("kirikiroid2.dll");
Storages.setTextEncoding("gbk");
```
---

