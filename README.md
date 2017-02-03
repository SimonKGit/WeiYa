# WeiYa
尾牙小程序
#### 基于微信公众号的签到、抽奖、发送弹幕程序
===========
### 注意事项：
1. 前端使用jquery，弹幕使用第三方canvas插件[【JBarrager】](https://github.com/Sailiy/JBarrager)
1. 后端使用spring mvc，数据库使用redis，微信api操作使用第三方sdk[【weixin-java-tools】](https://github.com/Wechat-Group/weixin-java-tools/releases)
1. jdk1.7+，tomcat使用7.0.73版本，因为使用websocket，目前只支持tomcat7支持websocket的版本,不支持tomcat8,9，后续会升级兼容新版本
1. 弹幕使用websocket建立长连接，前端使用canvas，经过测试可以经得住1000+人以上的交互发送消息
1. 登陆账号密码:root/root

===========