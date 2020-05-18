## 项目简介

>项目来源于：[https://github.com/ruou/hr](https://github.com/ruou/hr)

本系统基于**JSP+Servlet+C3P0+Mysql**。涉及技术少，易于理解，适合**JavaWeb初学者**学习使用。

**难度等级：简单**

## 技术栈

### 编辑器

Eclipse Version: 2019-12 (4.14.0)

### 前端技术

基础：html+css+JavaScript

框架：无

### 后端技术

Jsp+Servlet

数据库连接池：C3P0

JDBC工具：[Apache Commons DbUtils](http://commons.apache.org/proper/commons-dbutils/)

数据库：mysql 5.7.27（个人测试使用）

jdk版本：1.8.0_181（个人测试使用）

tomcat版本：8.5.34（个人测试使用）


## 本地运行

### Eclipse环境准备
1.[eclipse新增jdk](http://coderzcr.gitee.io/sensor-java-picture/pictures/Eclipse%E6%96%B0%E5%A2%9Ejdk.mp4)

2.[eclipse新增tomcat](http://coderzcr.gitee.io/sensor-java-picture/pictures/Eclipse%E6%96%B0%E5%A2%9Etomcat.mp4)

### 导入项目

> 若有疑惑可查看[视频版本](https://zhuanlan.zhihu.com/p/139051299)。

1.下载zip直接解压或安装git后执行克隆命令 
```
git clone https://github.com/ruou/hr.git
```
**若下载过慢可将github仓库复制到gitee上。** [查看视频](http://coderzcr.gitee.io/sensor-java-picture/pictures/GitHub下载慢怎么办？.mp4)


2.使用eclipse导入项目，配置jdk、tomcat和所需jar包。
项目所依赖jar包在**WebContent/WEB-INF/lib**文件夹下。

3.打开Navicat For Mysql，创建db_hr数据库，并运行**sql/db_hr.sql**。

4.修改**c3p0-config.xml**中数据库相关的内容。

5.发布到tomcat中，具体访问链接看tomcat配置，若未修改则[http://localhost:8080/hr](http://localhost:8080/hr)为登录页面。

系统中没有默认账号，需在数据库中添加账号。


## 注意
- 该项目未声明mysql、jdk、tomcat使用版本，以上版本号均为个人测试使用版本。
- 注意**修改c3p0-config.xml中数据库相关的内容。**


## 项目截图
![登录](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200508163601.png)
![系统管理员首页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200508163602.png)
![招聘管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200508163603.png)
![培训管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200508163604.png)
![薪金管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200508163605.png)
![用户管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200508163606.png)

## 声明
- 该项目收集于github，本人只是代为说明使用技术、注意点及启动方式，帮助大家进行学习交流。
- **若通过github地址无法下载该项目或无法正常运行，可私信我，本人免费协助。**


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


