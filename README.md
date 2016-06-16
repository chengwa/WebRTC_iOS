# WebRTC_iOS
关于WebRTC官网有一些介绍，但是因为官网在国外，你需要翻墙。<br>
我也写了三篇关于WebRTC的文章：<br>
[iOS下WebRTC音视频通话（一）](http://www.jianshu.com/p/36c11a3e49ed)<br>
[iOS下WebRTC音视频通话（二）-局域网内音视频通话](http://www.jianshu.com/p/aa9802c4296f)<br>
[iOS下WebRTC音视频通话（三）-外网音视频通话]() 这一篇还在准备中。<br>
示例工程中需要用到的WebRTC静态库，因为太大，我已上传到百度云盘,[地址在这](http://pan.baidu.com/s/1nvKpYRZ)。<br>

# 提醒
目录下有两个工程：<br>
`LocalWebRTC` 是局域网音视频通话的例子。不需要STUN、TURN服务器，也没有用到WebSocket。
`RemoteWebRTC`等待下次上传。

# 运行前准备
工程想要成功运行，你需要一些准备工作：
* 1.需要一个XMPP服务器，你也可以自己在本地搭建一个OpenFire服务器，作为你的XMPP服务器。<br>
关于XMPP部分，这里有几篇文章：<br>
[XMPP系列（一）:OpenFire环境搭建](http://blog.csdn.net/u011619283/article/details/46901363)<br>
[XMPP系列(二)----用户注册和用户登录功能](http://blog.csdn.net/u011619283/article/details/46958323)<br>
[XMPP系列(三）---获取好友列表、添加好友](http://blog.csdn.net/u011619283/article/details/46993627)<br>
[XMPP系列(四）---发送和接收文字消息，获取历史消息功能](http://blog.csdn.net/u011619283/article/details/47031895)<br>
[XMPP系列(五）---文件传输](http://blog.csdn.net/u011619283/article/details/47113685)<br>
* 2.从百度云盘将WebRTC的静态库下载下来后，加入工程内。
当然也可以用自己编译的WebRTC静态库，但是要将h264部分编译进去，iOS下视频编解码、传输用H264。
* 3.然后就可以成功运行示例工程了。


