#肖文辉（xiaowenhui）

 无线7期第二次课，作业要求

![](http://i.imgur.com/02lS6d1.jpg)


##一、ios网络模拟 

1. iphone安装开发者插件
2. 进入开发者进行设置

  Apple在iOS系统中预置了网络调试工具，设置——>开发者，如果手机上找不到这个，可以使用itool连接手机后，点击itool工具箱，点击一个设备管理工具，比如“实时桌面”，itools会提示安装开发者插件，安装完成后手机设置就能看到开发者选项

![](http://i.imgur.com/UpqCHe1.jpg)

 进入开发者设置，NETWORK LINK CONDITIONER

 ![](http://i.imgur.com/Nj5OSc0.jpg)


系统默认配置的网络条件还是很多的，其中：

1. 100%Loss —— 全丢包
2. 3G  —— 3G
3. DSL —— 电话线上网
4. Edge —— 2G网络
5. High Latency DNS —— 高延迟
6. Very Bad Network —— 网络状况不稳定

当然底部还有一个添加额外配置的选项可以自定义网络状况，进入系统默认的那些网络条件里，最低下有一个复制新建一个网络状况的选项，并可以自己设定参数，自己新建的可以删除。

![](http://i.imgur.com/6lXL9Ri.jpg)

![](http://i.imgur.com/AOPF5Hg.jpg)

![](http://i.imgur.com/3f5fXSo.jpg)

![](http://i.imgur.com/9hOz9Ao.jpg)

![](http://i.imgur.com/mQCONeF.jpg)

![](http://i.imgur.com/uTFymj8.jpg)

![](http://i.imgur.com/birF57W.jpg)

![](http://i.imgur.com/BdKeqNe.jpg)


## mac上模拟 

 使用教程网址： [http://nshipster.com/network-link-conditioner](http://nshipster.com/network-link-conditioner)

 下载地址：[https://developer.apple.com/downloads/?q=Hardware%20IO%20Tools](https://developer.apple.com/downloads/?q=Hardware%20IO%20Tools)


![](http://i.imgur.com/En0GujX.jpg)

![](http://i.imgur.com/hxi2ywH.jpg)

![](http://i.imgur.com/6JZXVpL.jpg)

![](http://i.imgur.com/WgaYS7N.jpg)


##二、使用抓包工具对app抓包并截图



1. 环境：`win7`
2. 工具：`Fiddler`
3. 抓包截图：

![](http://i.imgur.com/mEiMJ22.png)




##三、获取proxy tool的默认的ssl证书，并且在android or ios上面进行安装，并给出安装的截图

1. 环境：`win7`
2. proxy tool：`Fiddler`
3. 代理ip+端口号：`192.168.0.102 + 8888`（默认，可以自己修改）
4. 生成SSL证书：
![](http://i.imgur.com/eMqYXM9.jpg)

5. 手机上安装证书：手机设置好代理后，手机浏览器访问`192.168.0.102:8888/FiddlerRoot.cer`，安装证书
![](http://i.imgur.com/G2eZtLI.jpg)
![](http://i.imgur.com/ecvjwhw.jpg)

6. 访问百度手机网页，抓取https数据
![](http://i.imgur.com/0BYEtih.jpg)




## 四、编译一个android apk，并指出keystore目录

![](http://i.imgur.com/bQmJV1G.png) 

![](http://i.imgur.com/KUIK6iH.png)