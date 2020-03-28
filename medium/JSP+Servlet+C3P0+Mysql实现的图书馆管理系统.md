>  **本文存在[视频版本](https://zhuanlan.zhihu.com/p/115557947),请知悉**

----------

## 项目简介

>项目来源于：[https://gitee.com/GaoHuaiYu/library_management_system?_from=gitee_search](https://gitee.com/GaoHuaiYu/library_management_system?_from=gitee_search)

这次分享的也是毕设或课程设计选择一样很多的图书管理系统，适合新手入门。

本系统基于**JSP+Servlet+C3P0+Mysql**。涉及技术少，易于理解，适合**JavaWeb初学者**学习使用。

**难度等级：简单**

## 技术栈
### 编辑器

Eclipse Version: 2019-12 (4.14.0)

### 前端技术
基础：html+css+JavaScript

框架：[BootStrap](https://www.bootcss.com/)+[JQuery](https://jquery.com/)

### 后端技术
Jsp+Servlet

数据库：mysql 5.7.27（个人测试使用）

连接池: [C3P0](https://www.baidu.com/link?url=i4St4pZD-2QnhdI02uQYnprDqj9xRlDp2lUdDPM3cYSP2J6kjPGRN6sp97i1rNKM&wd=&eqid=bcfa6ca2000b5ac4000000025e745bc1)

JDBC工具：[Apache Commons DbUtils](http://commons.apache.org/proper/commons-dbutils/)

jdk版本：1.8.0_181（个人测试使用）

tomcat版本：8.5.34

## 本地运行

### Eclipse环境准备
1.[eclipse新增jdk](http://coderzcr.gitee.io/sensor-java-picture/pictures/Eclipse%E6%96%B0%E5%A2%9Ejdk.mp4)

2.[eclipse新增tomcat](http://coderzcr.gitee.io/sensor-java-picture/pictures/Eclipse%E6%96%B0%E5%A2%9Etomcat.mp4)

### 导入项目
1.下载zip直接解压或安装git后执行克隆命令 
```
https://gitee.com/GaoHuaiYu/library_management_system.git
```
2.使用eclipse打开项目，配置jdk、tomcat和所需jar包。
项目所依赖jar包在**WebContent/WEB-INF/lib**文件夹下。

3.打开Navicat For Mysql，运行**dzy.sql**文件。

4.修改**c3p0-config.xml**中数据库相关的内容。

5.发布到tomcat中，具体访问链接看tomcat配置，若未修改则[http://localhost:8080/myworkplus/](http://localhost:8080/myworkplus/)为登录页面。
系统有三种权限：系统管理员、图书管理员和读者。
系统管理员初始账号：admin 系统管理员初始密码：123
图书管理员初始账号：ghy   图书管理员初始密码：123
读者初始账号：fg  读者初始密码：123


## 注意
- 该项目未声明mysql、jdk、tomcat使用版本，以上版本号均为个人测试使用版本。
- 注意**修改c3p0-config.xml中数据库相关的内容。**


## 项目截图
![登录](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200323164101.png)
![系统管理员首页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200323164102.png)
![图书管理员首页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200323164103.png)
![读者首页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200323164104.png)

## 声明
- 该项目收集于gitee，本人只是代为说明使用技术、注意点及启动方式，帮助大家进行学习交流。
- **若通过gitee地址无法下载该项目或无法正常运行，可私信我，本人免费协助。**


#### 推荐阅读
- [JSP+Servlet+JDBC+DBCP2实现在线购书系统](https://mp.weixin.qq.com/s/kFHzkRtL6FNN9koaWAjDkg)
- [JSP+Servlet+JDBC实现的shine网上书城](https://mp.weixin.qq.com/s/GvfywZwg28IMYk5Q2ZWcOw)
- [JSP+Servlet+JDBC实现的云端汽修后台管理系统](https://mp.weixin.qq.com/s/kalGv5T8AZGxTnLHr2wDsA)
- [JSP+Servlet+JDBC实现的学生信息管理系统](https://mp.weixin.qq.com/s/K-H50joCXeE0cnwmtoqhJw)
- [JSP+Servlet+C3P0+Mysql实现的YCU movies电影网站](https://mp.weixin.qq.com/s/bJ1lGNDrVwzXx5z9dDaV-w)

---

欢迎关注我的公众号“**张有路**”，原创技术文章第一时间推送。

![](http://coderzcr.gitee.io/sensor-java-picture/pictures/qrcode.gif)
