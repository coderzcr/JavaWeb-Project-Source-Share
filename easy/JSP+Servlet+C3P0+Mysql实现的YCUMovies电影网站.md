>  **本文存在[视频版本](https://zhuanlan.zhihu.com/p/114689539),请知悉**

----------

## 项目简介

>项目来源于：[https://gitee.com/zhp0514/java_web_movie_website_project](https://gitee.com/zhp0514/java_web_movie_website_project)

这次分享一个电影网站，页面炫酷，需要有一定的前端功底。该网站存在一些bug，感兴趣的可以自行改改，也可以私信我。

本系统基于**JSP+Servlet+C3P0+Mysql**。涉及技术少，易于理解，适合**JavaWeb初学者**学习使用。

**难度等级：中等**

## 技术栈
### 编辑器

IntelliJ IDEA 2019.1.1 (Ultimate Edition)

### 前端技术
基础：html+css+JavaScript

框架：[BootStrap](https://www.bootcss.com/)+[ECharts](https://www.echartsjs.com/zh/index.html)+[JQuery](https://jquery.com/)

### 后端技术
Jsp+Servlet

数据库：mysql 5.7.27（个人测试使用）

连接池: [C3P0](https://www.baidu.com/link?url=i4St4pZD-2QnhdI02uQYnprDqj9xRlDp2lUdDPM3cYSP2J6kjPGRN6sp97i1rNKM&wd=&eqid=bcfa6ca2000b5ac4000000025e745bc1)

JDBC工具：[Apache Commons DbUtils](http://commons.apache.org/proper/commons-dbutils/)

jdk版本：1.8.0_181（个人测试使用）

tomcat版本：9.0.33（个人测试使用,且**版本必须为9以上**）

## 本地运行

1.下载zip直接解压或安装git后执行克隆命令 
```
https://gitee.com/zhp0514/java_web_movie_website_project.git
```
2.使用Idea打开项目，配置jdk、tomcat和所需jar包。
项目所依赖jar包在**web/WEB-INF/lib**文件夹下。

3.打开Navicat For Mysql，创建miviesdata数据库，复制**moviesdata.sql**中的文件内容运行。

4.修改**c3p0-config.xml**中数据库相关的内容。

5.发布到tomcat中，具体访问链接看tomcat配置，若未修改则[http://localhost:8080/java_web_movie_website_project_war_exploded/](http://localhost:8080/java_web_movie_website_project_war_exploded/)为登录页面。

初始账号：admin 初始密码：admin


## 注意
- 该项目未声明mysql、jdk、tomcat使用版本，以上版本号均为个人测试使用版本。
- 注意该项目的**tomcat版本必须大于等于9**。
- 注意**修改c3p0-config.xml中数据库相关的内容。**


## 项目截图
![首页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200320112601.png)
![登录](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200320112602.png)
![后台首页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200320112603.png)
![电影管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200320112604.png)

## 声明
- 该项目收集于gitee，本人只是代为说明使用技术、注意点及启动方式，帮助大家进行学习交流。
- **若通过gitee地址无法下载该项目或无法正常运行，可私信我，本人免费协助。**


#### 推荐阅读
- [JSP+Servlet+JDBC+DBCP2实现在线购书系统](https://mp.weixin.qq.com/s/kFHzkRtL6FNN9koaWAjDkg)
- [JSP+Servlet+JDBC实现的shine网上书城](https://mp.weixin.qq.com/s/GvfywZwg28IMYk5Q2ZWcOw)
- [JSP+Servlet+JDBC实现的云端汽修后台管理系统](https://mp.weixin.qq.com/s/kalGv5T8AZGxTnLHr2wDsA)
- [JSP+Servlet+JDBC实现的学生信息管理系统](https://mp.weixin.qq.com/s/K-H50joCXeE0cnwmtoqhJw)

---

欢迎关注我的公众号“**张有路**”，原创技术文章第一时间推送。

![公众号二维码](http://coderzcr.gitee.io/sensor-java-picture/pictures/qrcode.gif)

