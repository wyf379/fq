# FQWeb


番茄小说Web服务



## 使用
Web服务可在番茄小说设置界面开启，默认运行在9999端口

注：目前仅适配了`5.2.3.32`, `5.7.9.32`, `5.8.3.32`, `5.8.5.32`版本(其他版本不一定能用(可自行尝试，一般临近几个版本应该都能用)



## API列表
### 搜索
```
method：GET
url：http://localhost:9999/search?query=关键字&page=页数
```
### 获取书籍详情
```
method：GET
url：http://localhost:9999/info?book_id=书籍ID
```
### 获取书籍目录
```
method：GET
url：http://localhost:9999/catalog?book_id=书籍ID
```
### 获取章节内容
```
method：GET
url：http://localhost:9999/content?item_id=章节itemId
```
### 获取发现书籍
```
method：GET
url：http://localhost:9999/reading/bookapi/bookmall/cell/change/v1/
params：和番茄保持一致

method：GET
url：http://localhost:9999/reading/bookapi/new_category/landing/v/
params：和番茄保持一致
```



## 常见问题

1、提示"Failed to connect to localhost/127.0.0.1:9999"怎么办？

答：番茄没有打开或者后台被杀死，重新打开番茄即可

2、提示"failed to connect to localhost/127.0.0.1 (port 9999) from /127.0.0.1 (port xxxxx)"怎么办？

答：番茄后台被冻结了，请重新切换番茄到前台。将番茄后台改成无限制可能解决这个问题

## 免责声明
* 该Xposed模块仅供学习交流使用，使用者必须自行承担使用该模块所带来的风险和责任。

* 使用该Xposed模块可能导致设备不稳定、崩溃和数据丢失等问题。作者不对任何因使用该模块而导致的问题承担责任。

* 开发者保留对该Xposed模块的更新、修改、暂停、终止等权利，使用者应该自行确认其使用版本的安全性和稳定性。

* 任何人因使用该Xposed模块而导致的任何问题，作者不承担任何责任，一切后果由使用者自行承担。

* 对于使用该Xposed模块所产生的任何问题，作者不提供任何形式的技术支持和解决方案。

请在使用该Xposed模块之前认真阅读以上免责声明并自行权衡风险和利益，如有异议请勿使用。如果您使用了该Xposed模块，即代表您已经完全接受本免责声明。
