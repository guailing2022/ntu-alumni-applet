
### 项目介绍

- 你是否也有过这样的疑问？ 行业中的优秀校友咋联系？所在地的校友会哪里找？校友活动和资源整合怎么做？

- 以上答案，都在这里了!注册并登陆小程序后!

- 可以使用“通讯录查询”功能查询不同城市、公司、行业中的优秀校友
- 除校友通讯录的查询功能外

- 还可以在“校友组织”界面寻找自己所在地的校友会（再也不用担心找不到大部队咯～）


### 特点

- 无广告：本项目希望通过微信小程序，构建一款无广告，真实可靠的毕业校友通讯录。
- 简约：只做最基础功能，不臃肿，主打内容极简，功能简洁直击痛点
- 安全：保护校友的信息安全，隐私内容需要申请后可见。
- 方便：上传自己的个人信息，方便在需要时取得联系。小程序无需下载APP随用随走。


### 技术使用

- 项目使用微信小程序平台进行开发。
- 使用腾讯云开发技术，免费资源配额，	无需域名和服务器即可搭建。
- 小程序本身的即用即走，适合小工具的使用场景，也适合程序的开发。

### 项目效果截图

 ![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/185108_97d44d8d_9601221.png "屏幕截图.png")
 ![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/185219_7d68df93_9601221.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/185251_195c091a_9601221.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/185317_54bc83b7_9601221.png "屏幕截图.png")

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


 



至此完全配置完毕。

#### 在线演示：
![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060246_6fd3ef07_1810934.jpeg "小程序qr.jpg")

 


#### 如有疑问，可以联系我们： 
#### 作者微信:  cclinux0730 


