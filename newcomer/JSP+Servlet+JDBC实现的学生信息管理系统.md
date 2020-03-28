>  **本文存在[视频版本](https://zhuanlan.zhihu.com/p/114474382),请知悉**


----------

## 项目简介

>项目来源于：[https://gitee.com/liu_xu111/JavaWeb01](https://gitee.com/liu_xu111/JavaWeb01)

这次分享一个学生管理系统，我感觉这是程序员在大学时期的毕设和课程设计选择最多的课题，当然也包括我。
![doge](https://dss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=3244848201,3163658525&fm=26&gp=0.jpg)
本系统基于**JSP+Servlet+Jdbc**的学生信息管理系统。涉及技术少，易于理解，适合**JavaWeb初学者**学习使用。

**难度等级：简单**

## 技术栈
### 编辑器
Eclipse Version: 2019-12 (4.14.0)
### 前端技术
基础：html+css+JavaScript

框架：[H-ui](http://www.h-ui.net/)+[EasyUI](http://www.jeasyui.net/)

### 后端技术
Jsp+Servlet

数据库：mysql 5.7.27（个人测试使用）

jdk版本：1.8.0_181（个人测试使用）

tomcat版本：8.5.34（个人测试使用）

## 本地运行
### Eclipse环境准备
1.[eclipse新增jdk](http://coderzcr.gitee.io/sensor-java-picture/pictures/Eclipse%E6%96%B0%E5%A2%9Ejdk.mp4)

2.[eclipse新增tomcat](http://coderzcr.gitee.io/sensor-java-picture/pictures/Eclipse%E6%96%B0%E5%A2%9Etomcat.mp4)

### 导入项目
1.下载zip直接解压或安装git后执行克隆命令 
```
git clone https://gitee.com/liu_xu111/JavaWeb01.git
```

2.使用eclipse打开项目，配置jdk、tomcat和所需jar包。
项目所依赖jar包在**WebContent/WEB-INF/lib**文件夹下。

3.打开Navicat For Mysql，创建db_student_manager_web数据库，复制**com.ischoolbar.programmer.db.db_student_manager_web.sql**中的文件内容运行。

4.修改**com.ischoolbar.programmer.DbUtil**类中数据库相关的内容。

5.发布到tomcat中，[http://localhost:8080/StudentManagerWeb](http://localhost:8080/StudentManagerWeb)为登录页面。

辅导员初始账号：admin 初始密码：admin

其他账号使用辅导员创建即可

## 注意
- 该项目未声明mysql、jdk、tomcat使用版本，以上版本号均为个人测试使用版本
- 注意**修改com.ischoolbar.programmer.DbUti类中数据库相关的内容**


## 项目截图
![登录](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200319151101.png)
![首页](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200319151102.png)
![菜单](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200319151105.png)
![学生信息管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200319151103.png)
![班级信息管理](http://coderzcr.gitee.io/sensor-java-picture/pictures/blog20200319151104.png)

## 声明
- 该项目收集于gitee，本人只是代为说明使用技术、注意点及启动方式，帮助大家进行学习交流。
- **若通过gitee地址无法下载该项目或无法正常运行，可私信我，本人免费协助。**


#### 推荐阅读
- [项目分享JSP+Servlet+JDBC+DBCP2实现在线购书系统](https://mp.weixin.qq.com/s/kFHzkRtL6FNN9koaWAjDkg)
- [项目分享JSP+Servlet+JDBC实现的shine网上书城](https://mp.weixin.qq.com/s/GvfywZwg28IMYk5Q2ZWcOw)
- [项目分享JSP+Servlet+JDBC实现的云端汽修后台管理系统](https://mp.weixin.qq.com/s/kalGv5T8AZGxTnLHr2wDsA)


---

欢迎关注我的公众号“**张有路**”，原创技术文章第一时间推送。

![公众号二维码](http://coderzcr.gitee.io/sensor-java-picture/pictures/qrcode.gif)

