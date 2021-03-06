---
layout: post
title:  第三方集成索引
description: 对 IOS 开发中所用到的第三方库集成的总结
category: project
tag: ios, webrtc, Swift,rongcloud,youtube
---

## VOIP 通信

### Socket.io的集成
	
- [OC版本的集成][2]
- [C++版本的集成][3]

### WebRTC的集成

- [初期版本--基于apprtc-ios(libjingle)集成][4]
- [最终版本--利用最新的webrtc库完成语音通话][5]

### bug修复
 - [查询通话状态][18]
 - [问题处理-频繁打挂电话1][19]
 - [问题处理-频繁打挂电话2][20]
 - [问题处理-频繁打挂电话3][21]
 - [AURemoteIO中的IOThread崩溃][17]
 - [问题处理-过滤信令][22]


### 对voip通信的总结

- [WebRTC通信的原理][6]
- [完成voip通信的历程及注意事项][7]
- [Integration WebRTC In Our App][8]
- [修改WebRTC源代码编译出我们需要的动态库(禁用webrtc声音采集进行单向接听)][9]
- [修改WebRTC源代码编译出我们需要的动态库(替换webrtc声音采集进行双向通话)][15]
- [一对多通话设计][10]
- [WebRTC视频通话技术关键点][16]

## DJI OSMO

### 示例程序

- [Preview大疆设备的视频到手机上][11]

### 文档总结

- [集成OSMO开发设计][12]
- [集成OSMO的开发过程][14]
- [视频帧的时间戳][13]
- [接收 DJI inspire1 码流并解码][23]




[MaxwellQi]: https://maxwellqi.github.io "MaxwellQi"
[1]: {{ page.url }} ({{ page.title }})
[2]: https://github.com/MaxwellQi/Socket.io_Objective-C
[3]: https://github.com/MaxwellQi/Socket.io_CPP
[4]: https://github.com/MaxwellQi/WebRTC_IOS
[5]: https://github.com/MaxwellQi/WebRTC_IOS_final
[6]: http://w66g.com
[7]: http://w66g.com
[8]: http://w66g.com
[9]: http://w66g.com
[10]: http://w66g.com
[11]: http://w66g.com
[12]: http://w66g.com
[13]: http://w66g.com
[14]: http://w66g.com
[15]: http://w66g.com
[16]: http://w66g.com
[17]: https://maxwellqi.github.io/webrtc-iothread
[18]: https://maxwellqi.github.io/select-call-state
[19]: https://maxwellqi.github.io/quick-call-end1
[20]: https://maxwellqi.github.io/quick-call-end2
[21]: https://maxwellqi.github.io/quick-call-end3
[22]: https://maxwellqi.github.io/verify-signal
[23]: https://maxwellqi.github.io/dji-inspire1
