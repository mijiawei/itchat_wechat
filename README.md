# itchat_wechat
## 主要功能

1.根据序号,关键字自动回复消息(文本,图片,文件)
注：配置不是动态读取的。

2.支持消息转发到群组功能(文本消息)

## 使用方法

1.通过pip安装 itchat，xlrd（解析excel）

```
pip3 install itchat
pip3 install xlrd
```
2.运行auto_reply.py

```
python3 auto_reply.py
```
3.接着你会看见弹出二维码，用微信扫码登录（实际是登录网页版微信）自动回复变开始啦

4.在文件夹内会生成wechat的关键词条触发log
