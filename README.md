﻿weixinapi
=========

微信API接口


微信公众平台相信大家也不陌生，官方网站提供了一个简单的php程序Demo
因为微信平台采用HTTP方式承载微信的协议，而且不是双向通讯，也就是说只能由微信服务器主动请求我们的服务器。其实当你使用我开发的weixinapi包，你不用关心那么多的，呵呵。
看了api文档很久一段事件，今天突然恍然大雾，然后weixinapi的java版出来了

 微信API增加了HandleMessageListener监听器和HandleMessageAdapter适配器
微信服务器发送http请求过来后，会调用注册的所有监听器，的对应on方法



【更新】
----------------------完成官方20131029更新的消息接口------------------------

[2013-11-11] 更新了音乐消息的回复

[2013-11-11] 更新了视频消息的收发。

[2013-11-11] 更新了语音消息和语音识别消息兼容问题。

[2013-11-11] 更新了文本消息的属性，去除了funcFlag属性

[2013-11-11] 更新了图片消息的接收解析和被动发送解析，去除了funcFlag属性。

[2013-11-08] 添加了10月29日微信官方API中的视频消息

[2013-11-08] 添加了10月29日微信官方API中的语音识别消息

[2013-11-08] 更新了微信API最新接收事件推送{已关注事件推送、上报地理位置事件推送}接口

【微信模拟器】
下载地址：http://pan.baidu.com/s/11NRO4
