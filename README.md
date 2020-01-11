# 介绍
<center><h1>Supervisor多节点管理平台</h1></center>
<center><p>一个基于 Flask、Vue的前后端分离的Supervisor多节点管理平台</p></center>



-------

Tips: 由于在工作当中，多台服务器中运行了由Supervisor管理的众多服务，比如服务的状态控制，日志查看，在出现问题的时候需要去文档中查找对应的服务所对应的服务在ssh到服务器上面操作，总得说起来弊端就是管理起来起来比较松散、在问题出现时不能第一时间处理，于是本人利用了Supervisor 的`XML-RPC API`这一特性开发了一个用于管理Supervisor节点管理的一个后台。

![](https://github.com/guomaoqiu/multi-super-nodes/raw/master/screenhosts/info.png)

### 在线体验
预览地址：[http://super.sctux.com](http://super.sctux.com)

账号密码：admin/123456（所有账户都是一个密码）

### 完成度
#### 已完成:
[✔️ ] 完成后台用户角色、用户管理；

[✔️ ] 完成Supervisor节点信息录入，节点进程启动、关闭、重启、日志(标准输入输出)进行异常通知

#### 计划开发:
[⏸] 进程异常报警，计划采用Server酱、邮件、钉钉机器人


### 后台截图
* 登录界面
![](https://github.com/guomaoqiu/multi-super-nodes/raw/master/screenhosts/login.png)

* 后台用户管理
![](https://github.com/guomaoqiu/multi-super-nodes/raw/master/screenhosts/user-manager.png)

* Supervisor节点及进程管理界面
![](https://github.com/guomaoqiu/multi-super-nodes/raw/master/screenhosts/super-page.png)



### 反馈交流
如果在Demo体验过程中遇到什么问题可以在 github上提 [issues](https://github.com/guomaoqiu/multi-super-nodes/issues
) ，或者给发送邮件 2399447849@qq.com 


Bye the way : 最近打算跳槽，有需要人手的可以撩我哈😁【四川成都-Linux运维开发工程师】



