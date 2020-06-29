## 项目简介

>项目来源于：[https://gitee.com/huang_xiao_feng/carrentalsystem](https://gitee.com/huang_xiao_feng/carrentalsystem)

本系统基于**Maven+JSP+SSM+Mysql**实现的汽车租赁管理系统。简单实现了基础管理、系统管理，业务管理和统计分析。

**难度等级：中等**

## 技术栈

### 编辑器

IntelliJ IDEA 2019.1.1 (Ultimate Edition)

### 前端技术

基础：html+css+JavaScript

框架：[JQuery](https://www.runoob.com/jquery/jquery-tutorial.html)+[Layui](https://www.layui.com/)

### 后端技术

Spring+SpringMVC+Mybatis

模板引擎：JSP

数据库连接池：Druid

数据库：mysql 5.7.27（个人测试使用）

jdk版本：1.8.0_181（个人测试使用）

tomcat版本：8.5.34（个人测试使用）


## 本地运行

> 若有疑惑可查看[视频版本](https://zhuanlan.zhihu.com/p/138513664)。

1.下载zip直接解压或安装git后执行克隆命令 
```
git clone https://gitee.com/huang_xiao_feng/carrentalsystem.git
```
2.使用idea打开项目，配置maven、jdk即可。

3.打开Navicat For Mysql，创建**carrentalsystem**数据库，并运行**sql/carrentalsystem.sql**。

4.修改**resources\dataconnection.properties**中数据库相关的内容。

5.发布到tomcat中，具体访问链接看tomcat配置，若未修改则[http://localhost:8080](http://localhost:8080)为首页。

默认账号：admin
默认密码：123456



## 注意
- 该项目未声明mysql、jdk、tomcat使用版本，以上版本号均为个人测试使用版本。
- 注意**修改项目完整代码resources\dataconnection.properties中数据库相关的内容。**


## 项目截图
![登录](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200506161101.png)
![后台首页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200506161102.png)
![客户管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200506161103.png)
![车辆管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200506161104.png)
![车辆出租](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200506161105.png)
![系统管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200506161106.png)
![统计分析](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200506161107.png)

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


