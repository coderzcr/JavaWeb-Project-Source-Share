## 项目简介

>项目来源于：[https://gitee.com/2121/shop](https://gitee.com/2121/shop)

本系统是传智播客授课时的开发案例，基于**JSP+SSH+Mysql**的简单网上商城。在当代开发中，SSH的使用已经逐渐被SSM取代，但不代表我们不需要学习SSH，该系统简单，但功能齐全可以作为**SSH框架初学者**的入门项目。

**难度等级：中等**

## 技术栈

### 编辑器

Eclipse Version: 2019-12 (4.14.0)

### 前端技术

基础：html+css+JavaScript

框架：无

### 后端技术

SSH（struts2+spring+hibernate）

数据库：mysql 5.7.27（个人测试使用）

数据库连接池：C3P0

jdk版本：1.8.0_181（个人测试使用）

tomcat版本：8.5.34（个人测试使用）


## 本地运行

### Eclipse环境准备
1.[eclipse新增jdk](../../public/oldPicturesFromGitee/Eclipse%E6%96%B0%E5%A2%9Ejdk.mp4)

2.[eclipse新增tomcat](../../public/oldPicturesFromGitee/Eclipse%E6%96%B0%E5%A2%9Etomcat.mp4)

### 导入项目

> 若有疑惑可查看[视频版本](https://zhuanlan.zhihu.com/p/127840802)。

1.下载zip直接解压或安装git后执行克隆命令 
```
git clone https://gitee.com/2121/shop.git
```
2.使用eclipse**打开项目完整代码下的shop项目**，配置jdk、tomcat和所需jar包。
项目所依赖jar包在**WebRoot/WEB-INF/lib**文件夹下。

3.打开Navicat For Mysql，创建shop数据库，复制**项目完整代码\shop\shop.sql**中的内容，粘贴到Navicat中运行。

4.修改**项目完整代码\shop\src\jdbc.properties**中数据库相关的内容。

5.发布到tomcat中，具体访问链接看tomcat配置，若未修改则[http://localhost:8080/shop](http://localhost:8080/shop)为首页。
[http://localhost:8080/shop/admin/index.jsp](http://localhost:8080/shop/admin/index.jsp)为后台管理页面
初始账号：admin 初始密码：admin



## 注意
- 该项目未声明mysql、jdk、tomcat使用版本，以上版本号均为个人测试使用版本。
- 注意**修改项目完整代码\shop\src\jdbc.properties中数据库相关的内容。**


## 项目截图
![首页](../../public/oldPicturesFromGitee/blog20200409104601.png)
![分类](../../public/oldPicturesFromGitee/blog20200409104602.png)
![商品详情](../../public/oldPicturesFromGitee/blog20200409104603.png)
![购物车](../../public/oldPicturesFromGitee/blog20200409104604.png)
![后台首页](../../public/oldPicturesFromGitee/blog20200409104605.png)
![商品管理](../../public/oldPicturesFromGitee/blog20200409104606.png)
![订单管理](../../public/oldPicturesFromGitee/blog20200409104607.png)

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

![](../../public/oldPicturesFromGitee/qrcode.gif)


