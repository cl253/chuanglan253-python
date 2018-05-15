## chuanglan

**chuanglan-demo-python**

## 使用说明

- 下载python2.x版本，本demo仅支持python2.x版本

- 打开sms.py文件里面

- host填写：域名 例：smssh1.253.com

## python代码参数填写说明

```
import httplib
import urllib
import json
#参数的配置 请登录zz.253.com 获取以下API信息 ↓↓↓↓↓↓↓
#创蓝接口域名
host = "" 
#创蓝API账号
account  = ""
#创蓝API密码
password = ""

#端口号
port = 80

#版本号
version = "v1.1"

#余额查询的URL
balance_get_uri = "/msg/balance/json"

#普通短信发送的URL
sms_send_uri = "/msg/send/json" 
```
## 源码说明 

- 编码要求为utf-8,请先将编辑器底层语言设置为utf-8

- 带有特殊字符的内容无法直接提交,需先将特殊字符进行urlencode编码后方能提交

- 开发API可参考单元测试 doc/253云通讯PaaS短信云接口说明（JSON版）.docx



## 联系我们


[创蓝客服 链接](https://kefu253.udesk.cn/im_client/?web_plugin_id=47820={"name":"github"})


<img src="doc/kefu.jpg" width="20%" alt="创蓝客服"/>



## 文档链接- [api文档](https://www.253.com/#/document/api_doc/zz)

