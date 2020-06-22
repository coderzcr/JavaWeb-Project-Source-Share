<p align="center">
<a href="https://github.com/coderzcr/JavaWeb-Project-Source-Share" target="_blank">
	<img src="http://coderzcr.gitee.io/sensor-java-picture/pictures/zcr's blog.png" width="30%"/>
</a>
</p>

<p align="center">
  <a href="https://github.com/coderzcr/JavaWeb-Project-Source-Share"><img src="https://badgen.net/github/stars/coderzcr/JavaWeb-Project-Source-Share?icon=github&color=green" alt="star"></a>
  <a href="https://github.com/coderzcr/JavaWeb-Project-Source-Share"><img src="https://img.shields.io/badge/github-coderzcr-brightgreen.svg" alt="github"></a>
  <a href="#前言"><img src="https://img.shields.io/badge/QQ群-1029248321-brightgreen.svg" alt="QQ群"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/公众号-张有路-brightgreen.svg" alt="公众号"></a>
</p>

## 前言

**[若访问速度慢，图片无法加载问题，请访问GITEE版本](https://gitee.com/coderzcr/JavaWeb-Project-Source-Share)**

Hello，我是张有路！ 在这里，我将为您 

1）分享流行技术实现的JavaWeb源码（包括但不局限于Servlet、SSH、SSM、SpringBoot）及相关技术的讲解。 

2）对本仓库分享的代码进行免费的技术支持，但不涉及修改代码。 

3）若您有项目或技术方面需求的JavaWeb源码，我帮您寻找。比如您需要“汽车租赁系统”或者是使用SSM实现的系统，可加入q群**1029248321**大胆提出来，这里**不止分享源码，还会分享技术视频，热门教程，实用工具**，欢迎您的加入。。

4）**右上角Star+分享（仅限朋友圈、QQ空间、微博、超百人群）即可免费远程调试本仓库内任一项目1次。**

![](http://coderzcr.gitee.io/sensor-java-picture/pictures/202006221852.png)

5）另外，若您有修改代码、私人定制、远程协助的需求，也可直接联系qq310834626，但是要收费呦。

## 创建原因

大家好，我是一个Java后端开发，加上实习经历已经工作4年。

近日在知乎上发现了很多关于新手项目及工作经验的问题，比如
- [GitHub 上有哪些适合新手跟进的优质项目？](https://www.zhihu.com/question/22744854/answer/763206431)
- [有什么值得推荐的 Java、Web 练手项目？](https://www.zhihu.com/question/29444491/answer/507431828)
- [有哪些值得推荐的 Java 练手项目？](https://www.zhihu.com/question/56476038/answer/720699967)
- [如何在没有实际项目经验的情况下找到工作](https://zhuanlan.zhihu.com/p/26593436)

这些问题让我想起了大学时光。当时也是小白一枚，学的知识零散，不知如何利用，更不知道如何跟实际开发关联起来。所以我也有过以上困惑，开始寻找基础项目，把学到的知识利用起来。

我在网上找了很多项目，大部分无法正常启动，jdk版本不对、tomcat版本不对，甚至是缺失sql文件。就算项目正常启动，发现自己的水平达不到，很多写法自己不理解，让我很苦恼。所以，随着工作经验的提升，技术水平的增长，我能更好的分析项目、区分项目难度及是否能正常使用，我决定贡献一下自己的力量，帮助更多的Java使用者。

## 项目说明
目前这个项目只是初创阶段，很多细节还没有确定。但可以确定，这个仓库的目是分享优质JavaWeb项目帮助小白入门JavaWeb开发，协助JavaWeb开发者进阶，也让自己的技术水平能跟的上时代潮流。

仓库中分享的源码我将会以以下方式进行讲解。

- 将测试使用的jdk版本、tomcat版本、数据库版本和编辑器版本进行说明，保证版本一致的情况下正常使用。
- 分析项目中使用的前后端技术，并对难度进行分级，大家可以根据自己的水平选择相应难度的项目进行研究学习。
- 保证本项目中分享的项目能正常启动。
- 因源代码来源于网络，无法避免功能实现不完美或其他bug。我会将读者反馈的问题进行整理说明，避免大家踩坑。获取源码只是起步，能对源码进行修复才是大家需要的能力。

## 声明

该项目收集于gitee、github和其他开源方式，本人只是代为说明使用技术、注意点及启动方式，帮助大家进行学习交流，若作者不许可，可联系我删除。

## 分享内容

🌱🚀分享基于Servlet、SSH、SSM、SpringBoot等流行技术实现的JavaWeb项目。

### 难度等级说明

#### 声明

我是一个Java后端，前端涉猎不多，所以该仓库中的分级主要按照后端的难度进行分级，是个人想法，可能不太准确，若有错误，请多见谅。

#### 分级

本仓库中的项目难度分为5个等级，包括新手、简单、中等、困难和专家。

##### 新手等级

- Java基础。
- 数据库。需要具备数据库基础，会一种数据库的基本操作（mysql、oracle、sqlserver等）及通过JDBC操作数据库。
- 前端基础（html、css、javascript）。
- 前端框架基础。选择一个主要的前端框架（bootstrap、layui、easyui等）。
- JavaEE基础。Servlet、JSP。
- Web容器（tomcat等）。

##### 简单等级

在上一个等级的基础上，还需要具备如下的能力。

- 项目构建工具（maven、gradle等）。
- 基础java工具的使用（hutool、apache commons、Google Guava等）。
- 数据库连接池的使用（C3P0、DBCP、Druid、HikariCP等）。

##### 中等等级

中等等级的话基本上就可以用于简单的企业应用开发了。在上一个等级的基础上，还需要具备常用的企业开发框架使用的能力。

- Web层（Struts1、Struts2、Spring MVC）。
- Service层（Spring）。
- DAO层（Hibernate、Mybatis、Spring Data JPA）。
- 模板引擎（不止jsp,还有freemarker、velocity、thymeleaf等）。

其中Spring是重中之重，而且版本非常多，推荐学习现在最流行的Springboot，使用起来非常简单，而且集成其他框架十分便捷，基本上一个jar包，一个配置就能集成。


##### 困难等级

困难等级需要在上一个等级的基础上，具备提升服务高可用、高性能的能力。
- 前后端分离。
- 使用缓存改善性能（ehcache、CAFFEINE、redis等）。
- 使用应用服务器集群改善网站并发处理能力（nginx、haproxy等）。
- 数据库读写分离（mycat、rdrs、sharding-jdbc等）。
- 使用反向代理和 CDN 加速网站响应。
- 使用分布式文件系统和分布式数据库系统。
- 使用NoSQL（mogodb、redis等）。
- 使用搜索引擎（Lucene、ElasticSearch、Solandra等）。
- 使用消息队列削峰(ActiveMQ、RabbitMQ、Kafka)。
- 引入大数据服务平台（Hadoop）。

##### 专家等级

专家等级如何分，我个人水平也达不到，还需要继续摸索。

但是个人感觉要在具备服务高性能高可用的前提下，具备分布式服务的能力。

分布式结构就是将一个完整的系统，按照业务功能，拆分成一个个独立的子系统，在分布式结构中，每个子系统被称为服务。而且这些服务能独立运行在web容器中。比如SOA（面向服务的架构）和最近大热的微服务，其中最常用的框架有：
- Spring Cloud
- Dubbo

### 新手(★☆☆☆☆)

|源码编号|源码名称|源码来源|编辑器|前端关键字|后端关键字|文章详述|附带视频详述|百度云下载|问题备注|
|-|-|-|-|-|-|-|-|-|-|
|NEW202006221301|shine网上书城|[跳转](https://gitee.com/thuihuang/shine_bookshop)|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/JSP+Servlet+JDBC实现的shine网上书城.md)|[跳转](https://zhuanlan.zhihu.com/p/114001092)|[提取码：zjld](https://pan.baidu.com/s/1fzWCh9fqY6suJhFILzBT7w)|       |
|NEW202006221302|博客系统|[跳转](https://gitee.com/nanpingping/jsp-blog)|IDEA|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/JSP+Servlet+JDBC+Mysql实现的博客系统.md)|[跳转](https://zhuanlan.zhihu.com/p/116750137)|[提取码：okws](https://pan.baidu.com/s/1cukc7pltZkeoM25u54rPDA)|       |
|NEW202006221446|天才会议管理系统|[跳转](https://github.com/hegexunmeng/meeting-system)|Eclipse|html<br>css<br>JavaScript|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/JSP+Servlet+JDBC+Mysql实现的天才会议管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/117545363) |[提取码：06l6](https://pan.baidu.com/s/1oEd5xkCjgZQ7ZC_baiQhRQ)|       |
|NEW202006221455|云端汽修后台管理系统|[跳转](https://gitee.com/chenlinSir/CloudDemo-servlet)|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Layui|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/JSP+Servlet+JDBC实现的云端汽修后台管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/114188772) |[提取码：lv53](https://pan.baidu.com/s/1-izcQtdKd2z4FuJYVnRHEA)|       |
|NEW202006221458|学生信息管理系统|[跳转](https://gitee.com/liu_xu111/JavaWeb01)|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>h-ui<br>EasyUI|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/JSP+Servlet+JDBC实现的学生信息管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/114474382) |[提取码：8mkz](https://pan.baidu.com/s/1SuhQhOU-Y9B-wbsCjLdaDA)|       |
|NEW202006221501|学生成绩管理系统|[跳转](https://gitee.com/zzdoreen/SSMS)|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/JSP+Servlet+JDBC+mysql实现的学生成绩管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/141382924) |[提取码：9day](https://pan.baidu.com/s/158cXx0mavn2mxnvHdDu5IQ)|       |
|NEW202006221502|个人日记本系统|[跳转](https://gitee.com/wishwzp/Diary)|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/JSP+Servlet+JDBC+mysql实现的个人日记本系统.md)|[跳转](https://zhuanlan.zhihu.com/p/141379975) |[提取码：6b4f](https://pan.baidu.com/s/1V4nHpNusW08Z-OoThBfUUw)|       |
### 简单(★★☆☆☆)

|源码编号|源码名称|源码来源|编辑器|前端关键字|后端关键字|文章详述|附带视频详述|百度云下载|问题备注|
|-|-|-|-|-|-|-|-|-|-|
|EAS202006221507|图书馆管理系统|[跳转](https://gitee.com/GaoHuaiYu/library_management_system)|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0|[跳转](easy/JSP+Servlet+C3P0+Mysql实现的图书馆管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/115557947)|[提取码：ome3](https://pan.baidu.com/s/1wvQbELIac34h3xULPIEBeA)|       |
|EAS202006221509|网上蛋糕店|[跳转](https://gitee.com/PositiveMumu/CakesShop)|IDEA|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0|[跳转](easy/JSP+Servlet+C3P0+Mysql实现的网上蛋糕店.md)|[跳转](https://zhuanlan.zhihu.com/p/118471309)|[提取码：a3f6](https://pan.baidu.com/s/1xTd2gmGl7EeXmAU-K0gVLw)|       |
|EAS202006221511|YCU movies电影网站|[跳转](https://gitee.com/zhp0514/java_web_movie_website_project)|IDEA|html<br>css<br>JavaScript<br>Jquery<br>BootStrap<br>ECharts|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0|[跳转](easy/JSP+Servlet+C3P0+Mysql实现的YCUMovies电影网站.md)|[跳转](https://zhuanlan.zhihu.com/p/114689539) |[提取码：s4bb](https://pan.baidu.com/s/1E7bCLbxfhwSYoHMWovjkaw)|       |
|EAS202006221513|在线购书系统|[跳转](https://gitee.com/suimz_admin/BookShop)|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql<br>DBCP|[跳转](easy/JSP+Servlet+JDBC+DBCP2实现在线购书系统.md)|[跳转](https://zhuanlan.zhihu.com/p/104589778) |[提取码：46bv](https://pan.baidu.com/s/1zJX0hfnfHpESraXk-OMOEg)|1.数据库连接使用完毕后未关闭，多次操作后导致异常|
|EAS202006221515|苹果网上商城|[跳转](https://github.com/gpengDemo/Estore)|IDEA|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0|[跳转](easy/JSP+Servlet+C3P0+Mysql实现的苹果网上商城.md)|[跳转](https://zhuanlan.zhihu.com/p/120925119) |[提取码：nwxf](https://pan.baidu.com/s/1T6G2bhCbUPx2FVKKTDoH4A)|       |
|EAS202006221517|azhuo商城|[跳转](https://gitee.com/xuyizhuo/shopping)|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Layui|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0|[跳转](easy/JSP+Servlet+C3P0+Mysql实现的azhuo商城.md)|[跳转](https://zhuanlan.zhihu.com/p/121673478) |[提取码：ycrs](https://pan.baidu.com/s/1RlmaxcxIrIo7tJTuYRvYPQ)|       |
|EAS202006221518|简单新闻系统|[跳转](https://gitee.com/glotion/servlet-jsp_news)|IDEA|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0|[跳转](easy/JSP+Servlet+C3P0+Mysql实现的简单新闻系统.md)|[跳转](https://zhuanlan.zhihu.com/p/123246263) |[提取码：o5a5](https://pan.baidu.com/s/14rQNJrnBATPNeuvm3jnSNA)|       |
|EAS202006221520|人力资源管理系统|[跳转](https://github.com/ruou/hr)|Eclipse|html<br>css<br>JavaScript|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0<br>Apache Commons DbUtils|[跳转](easy/JSP+Servlet+JDBC+C3P0实现的人力资源管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/139051299) |[提取码：9csy](https://pan.baidu.com/s/1__xQZ40h-n1z9BNdNPDGFw)|       |
|EAS202006221522|dbExper宾馆管理系统|[跳转](https://github.com/mafulong/databaseExper-hotelMaster)|IDEA|html<br>css<br>JavaScript<br>Semantic UI<br>JQuery<br>Apache ECharts|Jsp<br>Servlet<br>jdbc<br>mysql<br>maven|[跳转](easy/Maven+JSP+Servlet+JDBC+Mysql实现的dbExper宾馆管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/115893887) |[提取码：78fh](https://pan.baidu.com/s/1FVIVMSHbEzGGuuRZh6xkiQ)|       |
|EAS202006221525|音乐库管理系统|[跳转](https://gitee.com/sunnyandgood/OnlineMusic)|IDEA|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0<br>maven|[跳转](easy/Maven+JSP+Servlet+C3P0+Mysql实现的音乐库管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/142863756) |[提取码：paqt](https://pan.baidu.com/s/1fpynxETaxD9iv8jrn31adg)|       |

### 中等(★★★☆☆)

|源码编号|源码名称|源码来源|编辑器|前端关键字|后端关键字|文章详述|附带视频详述|百度云下载|问题备注|
|-|-|-|-|-|-|-|-|-|-|
|MED202006221528|诚欣电子商城|[跳转](https://github.com/SuperiorNature/Java-Enterprise-electronic-mall)|Eclipse|html<br>css<br>JavaScript|Jsp<br>struts<br>jdbc<br>mysql|[跳转](medium/JSP+Struts+JDBC+Mysql实现的诚欣电子商城.md)|[跳转](https://zhuanlan.zhihu.com/p/146745084) |[提取码：cvsz](https://pan.baidu.com/s/13j7fXG9cxFxCsC_Py1cUOQ)|       |
|MED202006221530|校园宿舍管理系统|[跳转](https://gitee.com/passenger134/javaweb-sushe)|Eclipse|html<br>css<br>JavaScript|Jsp<br>struts<br>jdbc<br>mysql|[跳转](medium/JSP+Struts2+JDBC+Mysql实现的校园宿舍管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/128597135) |[提取码：jmgu](https://pan.baidu.com/s/1bjfOsgncJPd7S9C8Rg9tVw)|       |
|MED202006221531|大学生创新竞赛管理平台|[跳转](https://gitee.com/fly-liuhao/SCMS)|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Layui|Jsp<br>servlet<br>MyBatis<br>mysql|[跳转](medium/Layui+Servlet+MyBatis+Mysql实现的大学生创新竞赛管理平台.md)|[跳转](https://zhuanlan.zhihu.com/p/122402119) |[提取码：jhmr](https://pan.baidu.com/s/1fkDgsAZ2B5dpq4Klt_gbRg)|1.原仓库中未上传jar包及登录异常，现将修改过的源码上传到百度网盘上|
|MED202006221537|学生管理系统|[跳转](https://gitee.com/liu_xu111/javaSSH)|Eclipse|html<br>css<br>JavaScript|Jsp<br>SSH<br>mysql|[跳转](medium/JSP+SSH+Mysql实现的学生管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/127093868) |[提取码：x5ri](https://pan.baidu.com/s/1QR-50oYC0OfXDhAnph3M0A)|       |
|MED202006221539|传智播客网上商城|[跳转](https://gitee.com/2121/shop)|Eclipse|html<br>css<br>JavaScript|Jsp<br>SSH<br>mysql<br>c3p0|[跳转](medium/JSP+SSH+Mysql+C3P0实现的传智播客网上商城.md)|[跳转](https://zhuanlan.zhihu.com/p/127840802) |[提取码：uig7](https://pan.baidu.com/s/1OwHmrs4cM-6W2pB96Yweaw)|       |
|MED202006221540|租车系统|[跳转](https://github.com/1462656075/car)|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap<br>Apache ECharts|Jsp<br>SSH<br>mysql<br>DBCP|[跳转](medium/JSP+SSH+Mysql+DBCP实现的租车系统.md)|[跳转](https://zhuanlan.zhihu.com/p/146748074) |[提取码：w4pn](https://pan.baidu.com/s/1EJhqZ-pl88crUadwo0VNnA)|       |
|MED202006221542|图书馆预约占座管理系统|[跳转](https://gitee.com/gepanjiang/LibrarySeats)|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>EasyUI|Jsp<br>SSM<br>mysql|[跳转](medium/JSP+SSM+Mysql实现的图书馆预约占座管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/142867926) |[提取码：3gy1](https://pan.baidu.com/s/1hakrElxNgozJL5g4oYAVog)|1.因原gitee仓库无数据库文件且存在水印，经过本人修改，现将该仓库重新上传至[个人gitee仓库](https://gitee.com/coderzcr/LibrarySeats)。 |
|MED202006221545|学生成绩管理系统|[跳转](https://gitee.com/z77z/StuSystem)|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>H-ui|Jsp<br>SSM<br>mysql<br>druid|[跳转](medium/JSP+SSM+Mysql实现的学生成绩管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/145404370) |[提取码：pdez](https://pan.baidu.com/s/1JvtmS6EFRgI3lGu05DKXVQ)|       |
|MED202006221549|学生管理系统|[跳转](https://gitee.com/wu_yun_long/student_management_system)|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>c3p0|[跳转](medium/Maven+JSP+SSM+Mysql+C3P0实现的学生管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/134566305) |[提取码：6lbl](https://pan.baidu.com/s/1g-MSMnFmd3IsvEzXeW9-9g)|       |
|MED202006221546|校园失物招领网站|[跳转](https://github.com/wenlongup/LostAndFound)|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>EasyUI|Jsp<br>Spring<br>SpringMVC<br>Hibernate<br>mysql<br>c3p0|[跳转](medium/JSP+Spring+SpringMVC+Hibernate+Mysql实现的校园失物招领网站.md)|[跳转](https://zhuanlan.zhihu.com/p/138481010) |[提取码：1xns](https://pan.baidu.com/s/1nIa95ut_zBvdrsCvIvdoZg)|       |
|MED202006221550|汽车租赁管理系统|[跳转](https://gitee.com/huang_xiao_feng/carrentalsystem)|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Layui|Jsp<br>SSM<br>mysql<br>druid<br>maven|[跳转](medium/Maven+JSP+SSM+Mysql实现的汽车租赁管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/138513664) |[提取码：to49](https://pan.baidu.com/s/1FVlBQipMWuwkgtJXPs3a1Q)|       |
|MED202006221552|音乐网站|[跳转](https://gitee.com/coder_ze/iMusic)|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>DBCP<br>maven|[跳转](medium/Maven+JSP+SSM+Mysql实现的音乐网站.md)|[跳转](https://zhuanlan.zhihu.com/p/145403878) |[提取码：ecsf](https://pan.baidu.com/s/1aH4vhDO0kagmpw1YgIy5mg)|       |
|MED202006221554|家庭财务管理系统|[跳转](https://gitee.com/darlingzhangsh/graduation_project)|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Layui<br>Apache ECharts|thymeleaf<br>springboot<br>mybatis<br>mysql<br>HikariCP<br>maven|[跳转](medium/Thymeleaf+SpringBoot+Mybatis实现的家庭财务管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/132508106) |[提取码：rtcn](https://pan.baidu.com/s/1gQJkGVs05IcfhnZZ0gSWRQ)|       |
|MED202006221635|中小医院信息管理系统|[跳转](https://gitee.com/darlingzhangsh/graduation_project)|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|thymeleaf<br>springboot<br>jpa<br>mysql<br>HikariCP<br>maven<br>shiro<br>德卡D3 SDK<br>swagger|[跳转](medium/Thymeleaf+SpringBoot+SpringDataJPA实现的中小医院信息管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/132590561) |[提取码：h6mo](https://pan.baidu.com/s/1tFdce6hglEnBRxzVxb8D-Q)|       |
|MED202006221637|齐贤易游网旅游信息管理系统|[跳转](https://github.com/liuyongfei-1998/root)|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Layui|thymeleaf<br>springboot<br>mybatis<br>mysql<br>Tomcat-JDBC<br>maven|[跳转](medium/Thymeleaf+SpringBoot+Mybatis实现的齐贤易游网旅游信息管理系统.md)|[跳转](https://zhuanlan.zhihu.com/p/135932271) |[提取码：003c](https://pan.baidu.com/s/1hUeS6TYS3TwfTkA_907zWA)|       |
### 困难(★★★★☆)
|源码编号|源码名称|源码来源|编辑器|前端关键字|后端关键字|文章详述|附带视频详述|百度云下载|问题备注|
|-|-|-|-|-|-|-|-|-|-|
|DIF202006221640|黑马旅游网|[跳转](https://gitee.com/haoshunyu/travel)|IDEA|html<br>css<br>JavaScript<br>JQuery<br>Bootstrap|Jsp<br>servlet<br>jdbc<br>mysql<br>Druid<br>JdbcTemplate<br>maven|[跳转](difficult/Maven+JSP+Servlet+JDBC+Redis+Mysql实现的黑马旅游网.md)|[跳转](https://zhuanlan.zhihu.com/p/134288585) |[提取码：7w9r](https://pan.baidu.com/s/1FA_mzSPtEE_Az06KqfAagQ)|       |

### 专家(★★★★★)


## 自我介绍

我是张有路，山东大汉。

Java后端开发，4年工作经验。

博客：[coderzcr.top](http://coderzcr.top)

## 公众号

欢迎关注我的公众号“**张有路**”，原创技术文章第一时间推送。

<center>
    <img src="http://coderzcr.gitee.io/sensor-java-picture/pictures/qrcode.gif" style="width: 100px;">
</center>

## 联系我

 - [微博](https://weibo.com/u/6206251724)
 - [知乎](https://www.zhihu.com/people/zhangcaoran)
 - [github](https://github.com/coderzcr)
 - [gitee](https://gitee.com/coderzcr)
 - [掘金](https://juejin.im/user/5d3e9df8f265da1b7f29c772)
 - [segmentfault](https://segmentfault.com/u/coderzcr)
 - [csdn](https://blog.csdn.net/lowProgramer)
 - [博客园](https://www.cnblogs.com/zcr3108346262)
 - [简书](https://www.jianshu.com/u/e928dabb6a3e)
 - [v2ex](https://www.v2ex.com/member/coderzcr)
 - 310834626@qq.com（推荐）


