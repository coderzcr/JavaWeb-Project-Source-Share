## 项目简介

>项目来源于：[https://gitee.com/z77z/StuSystem](
https://gitee.com/z77z/StuSystem)

本系统是基于**JSP+SSM+Mysql**实现的学生成绩管理系统。主要实现的功能有教师管理、学生管理、课程管理、学生成绩管理。

**难度等级：中等**

## 技术栈

### 编辑器

Eclipse Version: 2020-03 (4.15.0)

### 前端技术

基础：html+css+JavaScript

框架：[JQuery](https://www.runoob.com/jquery/jquery-tutorial.html)+[H-ui](http://www.h-ui.net/index.shtml)

### 后端技术

Spring+SpringMVC+mybatis

模板引擎：JSP

数据库：mysql 5.7.27（个人测试使用）

jdk版本：1.8.0_251（个人测试使用）

tomcat版本：8.5.34（个人测试使用）

数据库连接池：druid

## 本地运行

### Eclipse环境准备
1.[eclipse新增jdk](https://www.bilibili.com/video/BV1o7411f7fa?p=1)

2.[eclipse新增tomcat](https://www.bilibili.com/video/BV1o7411f7fa?p=2)

### 导入项目

> 若有疑惑可查看[视频版本](https://zhuanlan.zhihu.com/p/145404370)。

1.下载zip直接解压或安装git后执行克隆命令。
```
git clone https://gitee.com/z77z/StuSystem.git
```
2.使用eclipse导入项目，配置jdk、tomcat和所需jar包。
项目所依赖jar包在**WebContent/WEB-INF/lib**文件夹下。

3.打开Navicat For Mysql，创建stusystem
数据库，并运行**stusystem.sql**文件。

4.修改**src\demo.properties**中数据库相关的内容。

5.发布到tomcat中，具体访问链接看tomcat配置，若未修改则[http://localhost:8080/StuSystem/](http://localhost:8080/StuSystem/)为登录页面。

该系统分为3种账号。
管理员初始账号：10003 系统管理员初始密码：admin 
教师初始账号：20001 教师初始密码：1234
学生初始账号: 10001 学生初始密码：1234




## 注意
- 该项目未声明mysql、jdk、tomcat使用版本，以上版本号均为个人测试使用版本。
- 注意**修改src\demo.properties**中数据库相关的内容。


## 项目截图
![登录页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200602183101.png)
![管理员首页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200602183102.png)
![教师信息管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200602183103.png)
![学生信息管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200602183104.png)
![课程信息管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200602183105.png)
![学生成绩管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200602183106.png)
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


