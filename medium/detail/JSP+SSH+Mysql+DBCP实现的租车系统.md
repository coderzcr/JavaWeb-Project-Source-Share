## 项目简介

>项目来源于：[https://github.com/1462656075/car](https://github.com/1462656075/car)

本系统是基于**JSP+SSH+Mysql+DBCP**实现的租车系统。在当代开发中，SSH的使用已经逐渐被SSM取代，但不代表我们不需要学习SSH，该系统简单，但功能齐全可以作为**SSH框架初学者**的入门项目。


**难度等级：中等**

## 技术栈

### 编辑器

Eclipse Version: 2019-12 (4.14.0)

### 前端技术

基础：html+css+JavaScript

框架：[JQuery](https://www.runoob.com/jquery/jquery-tutorial.html)+[Bootstrap](https://www.bootcss.com/)+[Apache ECharts](https://echarts.apache.org/zh/index.html)

### 后端技术

SSH（struts2+spring+hibernate）

数据库：mysql 5.7.27（个人测试使用）

数据库连接池：DBCP

jdk版本：1.8.0_181（个人测试使用）

tomcat版本：7.0.47（个人测试使用）


## 本地运行

### Eclipse环境准备
1.[eclipse新增jdk](http://coderzcr.gitee.io/sensor-java-picture/pictures/Eclipse%E6%96%B0%E5%A2%9Ejdk.mp4)

2.[eclipse新增tomcat](http://coderzcr.gitee.io/sensor-java-picture/pictures/Eclipse%E6%96%B0%E5%A2%9Etomcat.mp4)

### 导入项目

> 若有疑惑可查看[视频版本](https://zhuanlan.zhihu.com/p/146748074)。

1.下载zip直接解压或安装git后执行克隆命令 
```
git clone https://github.com/1462656075/car
```
**若下载过慢可将github仓库复制到gitee上。** [查看视频](https://www.bilibili.com/video/BV1o7411f7fa?p=3)

2.使用eclipse导入项目，配置jdk、tomcat和所需jar包。
项目所依赖jar包在**WebContent/WEB-INF/lib**文件夹下。

3.打开Navicat For Mysql，创建cars数据库，并运行**cars.sql**文件。

4.修改**config/jdbc.properties**中数据库相关的内容。

5.将**car\my\upload**文件夹发布到tomcat中，发布路径为/upload。若不配置，则项目中图片无法访问。

6.修改发布配置，去掉项目名称，否则无法正常访问。

7.发布到tomcat中，具体访问链接看tomcat配置，若未修改则[http://localhost:8080/login_index.do?role=1](http://localhost:8080/login_index.do?role=1)为首页。
默认账号：zs 默认密码：123

[http://localhost:8080/login_login.do?role=2](http://localhost:8080/login_login.do?role=2)
为后台管理登录页
初始账号：admin 初始密码：123



## 注意
- 该项目未声明mysql、jdk、tomcat使用版本，以上版本号均为个人测试使用版本。
- 注意**修改config/jdbc.properties中数据库相关的内容。**
- 将**car\my\upload**文件夹发布到tomcat中，发布路径为/upload。若不配置，则项目中图片无法访问。

## 项目截图
![首页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200604143801.png)
![客户登录](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200604143802.png)
![汽车详情](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200604143803.png)
![租车](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200604143804.png)
![我的订单](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200604143805.png)
![车辆管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200604143806.png)
![订单管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200604143807.png)

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


