# 短信网关简单设计

### 大纲如下:


整体路线:

	客户端 -- http/https -- 公网机器 -- http -- 第三方短信平台




授权模式:

	授权码 + 条数(可变更)

公网内网客户端统一. 除了授权码可能不一样。

通道:

	预警通道(高)
	验证码通道(高)
	内部人员通道(中)
	消息通知(中)
	推广通道(低)


公网机器:

	N + 1 模式

根据需要,入口机器可能有N台。(也算是通道的一部分)

[待完善。。。]()



日期: 2016年01月26日

作者: [铁锚 http://blog.csdn.net/renfufei](http://blog.csdn.net/renfufei)

