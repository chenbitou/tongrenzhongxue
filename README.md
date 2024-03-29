 
### 项目介绍


 校友圈小程序是一个公益性的信息发布及交流的平台，为广大校友及海南老乡之间的文化交流、商务合作、资源共享，创造更加高效、便利的环境，构建家乡人之间诚信、合作、互利、共赢的良好局面。  同时，拥有自己小程序的入驻商家，可在平台添加自己的小程序二维码，为自己业务增加流量入口。

 

### 技术使用

项目使用微信小程序平台进行开发。
使用腾讯云开发技术，免费资源配额，	无需域名和服务器即可搭建。
小程序本身的即用即走，适合小工具的使用场景，也适合程序的开发。

### 项目效果截图

![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060621_49d4c43f_1810934.png "1.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060627_55436a5e_1810934.png "2.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060634_4ff55319_1810934.png "3.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060641_80dacd4d_1810934.png "4.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060648_39c1f771_1810934.png "5.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060655_c5db02ba_1810934.png "6.png")

      

### 部署教程：

#### 1 源码解压
 

#### 2 在微信小程序开发工具中导入 解压后的文件夹
![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060102_2f8d8f02_1810934.png "导入.png")


 

#### 3 开通云开发环境
  参考微信官方文档：https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html

#### 4 数据库操作
建立数据库集合
t_user
t_album
t_info
t_setup

#### 5 云函数及配置
本项目使用到了一个云函数cloud
在云函数cloudfunctions文件夹下选择一个云函数cloud , 右键选择在终端中打开,然后执行 
npm install –product

![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060144_cb89de4a_1810934.png "云函数.png")



 

打开cloudfunctions/cloud/comm/config.js文件，配置环境ID

![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060154_ea7c36a1_1810934.png "云函数配置.png")


 


#### 6  客户端配置
打开miniprogram/helper/setting.js文件，配置环境ID

![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060203_71503106_1810934.png "客户端配置.png")

 

#### 7  上传云函数&指定云环境ID

 ![输入图片说明](https://images.gitee.com/uploads/images/2021/0828/101935_d116bfc6_9645159.png "上传到云.png")


至此完全配置完毕。

#### 在线演示：
 ![输入图片说明](https://images.gitee.com/uploads/images/2021/0719/100637_5429f9d1_9240987.jpeg "ccplat-小程序QR.jpg")

 


#### 如有疑问，欢迎骚扰联系我鸭： 
#### 俺的微信:  cclinux0730


