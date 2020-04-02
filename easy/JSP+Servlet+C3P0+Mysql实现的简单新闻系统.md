## 项目简介

>项目来源于：[https://gitee.com/glotion/servlet-jsp_news](https://gitee.com/glotion/servlet-jsp_news)

本系统基于**JSP+Servlet+C3P0+Mysql**。涉及技术少，易于理解，适合**JavaWeb初学者**学习使用。

**难度等级：简单**

## 技术栈

### 编辑器

IntelliJ IDEA 2019.1.1 (Ultimate Edition)

### 前端技术

基础：html+css+JavaScript

框架：[Bootstrap](https://www.bootcss.com/)+[wangEditor - 轻量级web富文本编辑器](http://www.wangeditor.com/)

### 后端技术

Jsp+Servlet

数据库连接池：C3P0

数据库：mysql 5.7.27（个人测试使用）

jdk版本：1.8.0_181（个人测试使用）

tomcat版本：9.0.33（个人测试使用）


## 本地运行

> 若有疑惑可查看[视频版本](https://zhuanlan.zhihu.com/p/123246263)。

1.下载zip直接解压或安装git后执行克隆命令 
```
https://gitee.com/glotion/servlet-jsp_news.git
```
2.使用Idea打开项目，配置jdk、tomcat和所需jar包。

3.打开Navicat For Mysql，运行**config/news_table.sql**。

4.修改**config/c3p0-config.xml**中数据库相关的内容。
因使用原版会导致插入数据乱码问题，建议将配置文件更换为以下配置。
```xml
<?xml version="1.0" encoding="UTF-8"?>
<c3p0-config>
	<default-config>
		<property name="driverClass">com.mysql.cj.jdbc.Driver</property>
		<property name="jdbcUrl">jdbc:mysql://localhost:3306/news?serverTimezone=Asia/Shanghai&amp;characterEncoding=UTF-8</property>
		<property name="user">root</property>
		<property name="password">root</property>
	</default-config>
</c3p0-config>
```

5.发布到tomcat中，具体访问链接看tomcat配置，若未修改则[http://localhost:8080/](http://localhost:8080/)为首页。
[http://localhost:8080/admin](http://localhost:8080/admin)为后台登录首页。

因数据库中没有存在账户数据，需要自行插入用户信息。



## 注意
- 该项目未声明mysql、jdk、tomcat使用版本，以上版本号均为个人测试使用版本。
- 注意**修改config/c3p0-config.xml中数据库相关的内容。**
- 数据库中没有存在账户数据，需要自行插入用户信息。


## 项目截图
![首页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200402164701.png)
![文章详情页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200402164702.png)
![后台登录页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200402164703.png)
![分类管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200402164704.png)
![文章管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200402164705.png)
![发表新闻](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200402164706.png)

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

