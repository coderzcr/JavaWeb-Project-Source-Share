## 项目简介

>项目来源于：[https://gitee.com/sunnyandgood/OnlineMusic](https://gitee.com/sunnyandgood/OnlineMusic)

本系统基于**Maven+JSP+Servlet+C3P0+Mysql**实现的音乐库管理系统。简单实现了充值、购买歌曲、poi数据导入导出、歌曲上传下载、歌曲播放、用户注册登录注销等功能。

**难度等级：简单**

## 技术栈

### 编辑器

IntelliJ IDEA 2020.1.1 (Ultimate Edition)

### 前端技术

基础：html+css+JavaScript

框架：[JQuery](https://www.runoob.com/jquery/jquery-tutorial.html)+[Bootstrap](https://www.bootcss.com/)

### 后端技术

JSP+Servlet

数据库连接池：c3p0

数据库：mysql 5.7.27（个人测试使用）

jdk版本：1.8.0_251（个人测试使用）

web服务器：maven插件maven-jetty-plugin 6.1.7

项目构建：Maven 3.6.3（个人测试使用）


## 本地运行

> 若有疑惑可查看[视频版本](https://zhuanlan.zhihu.com/p/142863756)。

1.下载zip直接解压或安装git后执行克隆命令 
```
git clone https://gitee.com/sunnyandgood/OnlineMusic.git
```
2.使用idea打开项目，配置maven、jdk即可。

3.打开Navicat For Mysql，创建**onlinemusic**数据库，并运行**onlinemusic.sql**。

4.修改**resources\c3p0-config.xml**中数据库相关的内容。

5.执行jetty:run-exploded，具体访问链接看jetty配置，若未修改则[http://localhost:8888](http://localhost:8888)为用户首页。

默认用户账户：123 默认用户密码：123

[http://localhost:8888/admin_login.jsp](http://localhost:8888/admin_login.jsp)为管理员登录页面。

默认管理员账号：admin
默认管理员密码：admin


## 注意
- 该项目未声明mysql、jdk、maven使用版本，以上版本号均为个人测试使用版本。
- 注意**修改resources\c3p0-config.xml中数据库相关的内容。**


## 项目截图
![用户登录](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200522151201.png)
![用户信息](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200522151202.png)
![音乐库](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200522151203.png)
![管理员登录](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200522151204.png)
![音乐管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200522151205.png)
![歌曲分类管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200522151206.png)

## 声明
- 该项目收集于gitee，本人只是代为说明使用技术、注意点及启动方式，帮助大家进行学习交流。
- **若通过gitee地址无法下载该项目或无法正常运行，可私信我，本人免费协助。**


#### 推荐阅读
- [JSP+Servlet+JDBC+DBCP2实现在线购书系统](https://mp.weixin.qq.com/s/kFHzkRtL6FNN9koaWAjDkg)
- [JSP+Servlet+JDBC实现的shine网上书城](https://mp.weixin.qq.com/s/GvfywZwg28IMYk5Q2ZWcOw)
- [JSP+Servlet+JDBC实现的云端汽修后台管理系统](https://mp.weixin.qq.com/s/kalGv5T8AZGxTnLHr2wDsA)
- [JSP+Servlet+JDBC实现的学生信息管理系统](https://mp.weixin.qq.com/s/K-H50joCXeE0cnwmtoqhJw)
- [JSP+Servlet+C3P0+Mysql实现的YCU movies电影网站](https://mp.weixin.qq.com/s/bJ1lGNDrVwzXx5z9dDaV-w)
- [JSP+Servlet+C3P0+Mysql实现的图书馆管理系统](https://mp.weixin.qq.com/s/MdGVYX_8t-CiOasghGPrRw)

---

本篇已收录于个人GitHub仓库[https://github.com/coderzcr/JavaWeb-Project-Source-Share](https://github.com/coderzcr/JavaWeb-Project-Source-Share)，欢迎Star。


欢迎关注我的公众号“**张有路**”，原创技术文章第一时间推送。

![](http://coderzcr.gitee.io/sensor-java-picture/pictures/qrcode.gif)


