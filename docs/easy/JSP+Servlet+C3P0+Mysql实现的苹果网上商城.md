## 项目简介

>项目来源于：[https://github.com/gpengDemo/Estore](https://github.com/gpengDemo/Estore)


本系统基于**JSP+Servlet+C3P0+Mysql**。涉及技术少，易于理解，适合**JavaWeb初学者**学习使用。

**难度等级：简单**

## 技术栈

### 编辑器

IntelliJ IDEA 2019.1.1 (Ultimate Edition)

### 前端技术

基础：html+css+JavaScript

框架：[Bootstrap](https://www.bootcss.com/)+[JQuery](https://jquery.com/)

### 后端技术

Jsp+Servlet

数据库连接池：C3P0

数据库：mysql 5.7.27（个人测试使用）

jdk版本：1.8.0_181（个人测试使用）

tomcat版本：9.0.33（个人测试使用）



## 本地运行

> 若有疑惑可查看[视频版本](https://zhuanlan.zhihu.com/p/120925119)。视频版本中为了加快下载速度，已将github仓库复制到gitee上。[查看视频 GitHub下载慢怎么办？](http://coderzcr.gitee.io/sensor-java-picture/pictures/GitHub下载慢怎么办？.mp4)

1.下载zip直接解压或安装git后执行克隆命令 

```
https://github.com/gpengDemo/Estore.git
```

2.使用Idea打开项目，配置jdk、tomcat和所需jar包。配置tomcat时，将**upload文件夹**配置为外部资源，否则图片显示将异常。

3.打开Navicat For Mysql，新建名称为**estore**的数据库，复制**estore.sql**中的内容到Navicat运行。

4.修改**c3p0-config.xml**中数据库相关的内容。

5.发布到tomcat中，具体访问链接看tomcat配置，若未修改则[http://localhost:8080/Estore_Web_exploded/](http://localhost:8080/Estore_Web_exploded/)为商城首页。


## 注意
- 该项目未声明mysql、jdk、tomcat使用版本，以上版本号均为个人测试使用版本。
- 注意**修改c3p0-config.xml中数据库相关的内容。**
- 注意将**upload文件夹**发布，否则会出现图片不显示的问题。
- 根据仓库下面的评论，改项目存在bug，需要自己修改，bug如下。

> 1、不能登录，使用你的账号登录不了，我注册的也登陆不了。
> 2、不登陆也能提交订单，拦截器有问题。
> 3、后台登陆问题，登录之后就退出不了。



## 项目截图
![注册](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200330144801.png)
![首页1](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200330144802.png)
![首页2](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200330144803.png)
![首页3](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200330144804.png)
![详情页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200330144805.png)
![购物车](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200330144806.png)

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

