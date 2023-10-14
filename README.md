<p align="center">
<a href="https://github.com/coderzcr/JavaWeb-Project-Source-Share" target="_blank">
	<img src="http://coderzcr.gitee.io/sensor-java-picture/pictures/zcr's blog.png" width="30%"/>
</a>
</p>

<p align="center">
  <a href="https://github.com/coderzcr/JavaWeb-Project-Source-Share"><img src="https://badgen.net/github/stars/coderzcr/JavaWeb-Project-Source-Share?icon=github&color=green" alt="star"></a>
  <a href="https://github.com/coderzcr/JavaWeb-Project-Source-Share"><img src="https://img.shields.io/badge/github-coderzcr-brightgreen.svg" alt="github"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/公众号-张有路-brightgreen.svg" alt="公众号"></a>
</p>


## 前言

Hello，我是张有路！ 在这里，我将为您分享流行技术实现的JavaWeb源码（包括但不局限于Servlet、SSH、SSM、SpringBoot、SpringCloud）及相关技术的讲解。 

如需帮助，可加作者微信**zr-310834626**,拉您入群。可远程协助启动Java项目，寻找JavaWeb源码，代码定制等。

## 项目说明
目前这个项目只是初创阶段，很多细节还没有确定。但可以确定，这个仓库的目是分享优质JavaWeb项目帮助小白入门JavaWeb开发，协助JavaWeb开发者进阶，也让自己的技术水平能跟的上时代潮流。

仓库中分享的源码我将会以以下方式进行讲解。

- 将测试使用的jdk版本、tomcat版本、数据库版本和编辑器版本进行说明，保证版本一致的情况下正常使用。
- 分析项目中使用的前后端技术，并对难度进行分级，大家可以根据自己的水平选择相应难度的项目进行研究学习。
- 保证本项目中分享的项目能正常启动。
- **因源代码来源于网络，无法避免功能实现不完美或其他bug。我会将读者反馈的问题进行整理说明，避免大家踩坑。获取源码只是起步，能对源码进行修复才是大家需要的能力。**

## 创建原因

大家好，我是一个Java后端开发，加上实习经历已经工作5年。

近日在知乎上发现了很多关于新手项目及工作经验的问题，比如
- [GitHub 上有哪些适合新手跟进的优质项目？](https://www.zhihu.com/question/22744854/answer/763206431)
- [有什么值得推荐的 Java、Web 练手项目？](https://www.zhihu.com/question/29444491/answer/507431828)
- [有哪些值得推荐的 Java 练手项目？](https://www.zhihu.com/question/56476038/answer/720699967)
- [如何在没有实际项目经验的情况下找到工作](https://zhuanlan.zhihu.com/p/26593436)

这些问题让我想起了大学时光。当时也是小白一枚，学的知识零散，不知如何利用，更不知道如何跟实际开发关联起来。所以我也有过以上困惑，开始寻找基础项目，把学到的知识利用起来。

我在网上找了很多项目，大部分无法正常启动，jdk版本不对、tomcat版本不对，甚至是缺失sql文件。就算项目正常启动，发现自己的水平达不到，很多写法自己不理解，让我很苦恼。所以，随着工作经验的提升，技术水平的增长，我能更好的分析项目、区分项目难度及是否能正常使用，我决定贡献一下自己的力量，帮助更多的Java使用者。

## 声明

该项目收集于gitee、github和其他开源方式，本人只是代为说明使用技术、注意点及启动方式，帮助大家进行学习交流，若作者不许可，可联系我删除。

## 分享内容

🌱🚀分享基于Servlet、SSH、SSM、SpringBoot、SpringCloud等流行技术实现的JavaWeb项目。

### 推荐项目

👇根据**源码编号**可在下面内容中找到更详细的说明👇

|源码编号|源码名称|推荐原因|
|-|-|-|
|NEW202007311522、MED202007311557、MED202007311603|模仿天猫网站|以Servlet、SSH、SSM三种形式实现了天猫网站，并附带详细的实现思路、说明文档|
|EAS202008031933|学生管理系统|附带视频教程，跟随视频学习效率高且出错的可能性比较小|
|MED202103171416|高校毕业生就业信息管理系统|附带论文和各种流程图|
|DIF202006291932|在线音乐网站|附带实现思路、说明文档，适合学习|
|DIF202007091023|微人事|附带实现思路、说明文档，适合学习|
|DIF202212101509、EXP202212101413|小说精品屋|以SpringBoot、SpringCloud两种种形式实现了小说网站，并附带详细的说明文档|

### 快速开发脚手架
快速开发脚手架的主要目的是封装通用功能，开发人员只需关注业务代码，快速开发。
目前流行的框架为SpringBoot、SpringCloud，所以只收集这两种技术的脚手架。若无特殊技术要求，建议使用这两种技术开发系统。

#### SpringBoot
|源码名称|前后端分离|推荐原因|详述|
|-|-|-|-|
|RuoYi|否|若依基于SpringBoot2.0的权限管理系统 易读易懂、界面简洁美观，文档齐全。核心技术采用SpringBoot、MyBatis、Shiro、Thymeleaf、Bootstrap、Vue没有任何其它重度依赖。直接运行即可用|[跳转](https://gitee.com/y_project/RuoYi)|
|RuoYi-Vue|是|RuoYi前后端分离版本。 基于SpringBoot，Spring Security，JWT，Vue & Element 的前后端分离权限管理系统，同时提供了 Vue3 的版本|[跳转](https://gitee.com/y_project/RuoYi-Vue)|
|Snowy|是|采用SpringBoot+MybatisPlus+AntDesignVue+Vite 等更多优秀组件及前沿技术开发，注释丰富，代码简洁，开箱即用！|[跳转](https://gitee.com/xiaonuobase/snowy)|

#### SpringCloud
|源码名称|推荐原因|详述|
|-|-|-|
|RuoYi-Cloud|RuoYi微服务版本。基于Spring Boot、Spring Cloud & Alibaba的分布式微服务架构权限管理系统，同时提供了 Vue3 的版本|[跳转](https://gitee.com/y_project/RuoYi-Cloud)|

### 难度等级说明

本仓库中的项目难度分为5个等级，包括新手、简单、中等、困难和专家。

我是Java后端，前端涉猎不多，所以该仓库中的分级主要按照后端的难度进行分级，可能不太准确，请多见谅。

### 新手(★☆☆☆☆)[点我查看新手要求](newcomer/newcomer.md)

|源码编号|源码名称|编辑器|前端关键字|后端关键字|详述|
|-|-|-|-|-|-|
|NEW202006221301|shine网上书城|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202006221301.md)|
|NEW202006221302|博客系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202006221302.md)|
|NEW202006221446|天才会议管理系统|Eclipse|html<br>css<br>JavaScript|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202006221446.md)|
|NEW202006221455|云端汽修后台管理系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Layui|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202006221455.md)|
|NEW202006221458|学生信息管理系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>h-ui<br>EasyUI|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202006221458.md)|
|NEW202007020947|教务系统(学生信息管理系统)|IDEA|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202007020947.md)|
|NEW202006221501|学生成绩管理系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202006221501.md)|
|NEW202006221502|个人日记本系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202006221502.md)|
|NEW202006281404|泊车系统|Eclipse|html<br>css<br>JavaScript<br>Jquery|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202006281404.md)|
|NEW202006281642|教学评价系统|Eclipse|html<br>css<br>JavaScript|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202006281642.md)|
|NEW202007012128|托马斯网上零食商城|Eclipse|html<br>css<br>JavaScript|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202007012128.md)|
|NEW202007012223|二手交易网站|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202007012223.md)|
|NEW202007311522|模仿天猫网站|IDEA|html<br>css<br>JavaScript<br>jQuery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202007311522.md)|
|NEW202010170913|超市管理系统|Eclipse|html<br>css<br>JavaScript|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202010170913.md)|
|NEW202212051538|挂号预约系统|IDEA|html<br>css<br>JavaScript|Jsp<br>Servlet<br>jdbc<br>mysql|[跳转](newcomer/preview/NEW202212051538.md)|

### 简单(★★☆☆☆)[点我查看简单要求](easy/easy.md)

|源码编号|源码名称|编辑器|前端关键字|后端关键字|详述|
|-|-|-|-|-|-|
|EAS202006221507|图书馆管理系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0|[跳转](easy/preview/EAS202006221507.md)|
|EAS202006221509|网上蛋糕店|IDEA|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0|[跳转](easy/preview/EAS202006221509.md)|
|EAS202006221511|YCU movies电影网站|IDEA|html<br>css<br>JavaScript<br>Jquery<br>BootStrap<br>ECharts|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0|[跳转](easy/preview/EAS202006221511.md)|
|EAS202006221513|在线购书系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql<br>DBCP|[跳转](easy/preview/EAS202006221513.md)|
|EAS202006291902|传智书城|Eclipse|html<br>css<br>JavaScript|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0|[跳转](easy/preview/EAS202006291902.md)|
|EAS202006221515|苹果网上商城|IDEA|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0|[跳转](easy/preview/EAS202006221515.md)|
|EAS202006221517|azhuo商城|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Layui|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0|[跳转](easy/preview/EAS202006221517.md)|
|EAS202006221518|简单新闻系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0|[跳转](easy/preview/EAS202006221518.md)|
|EAS202006221520|人力资源管理系统|Eclipse|html<br>css<br>JavaScript|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0<br>Apache Commons DbUtils|[跳转](easy/preview/EAS202006221520.md)|
|EAS202006221522|dbExper宾馆管理系统|IDEA|html<br>css<br>JavaScript<br>Semantic UI<br>JQuery<br>Apache ECharts|Jsp<br>Servlet<br>jdbc<br>mysql<br>maven|[跳转](easy/EAS202006221522.md)|
|EAS202006221525|音乐库管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0<br>maven|[跳转](easy/preview/EAS202006221525.md)|
|EAS202006281628|投票系统|eclipse|html<br>css<br>JavaScript<br>JQuery|Jsp<br>Servlet<br>jdbc<br>mysql<br>c3p0|[跳转](easy/preview/EAS202006281628.md)|
|EAS202008031933|学生管理系统|eclipse|html<br>css<br>JavaScript<br>JQuery<br>BootStrap|Jsp<br>Servlet<br>jdbc<br>mysql<br>dbcp|[跳转](easy/preview/EAS202008031933.md)|

### 中等(★★★☆☆)[点我查看中等要求](medium/medium.md)

|源码编号|源码名称|编辑器|前端关键字|后端关键字|详述|
|-|-|-|-|-|-|
|MED202006221528|诚欣电子商城|Eclipse|html<br>css<br>JavaScript|Jsp<br>struts<br>jdbc<br>mysql|[跳转](medium/preview/MED202006221528.md)|
|MED202006221530|校园宿舍管理系统|Eclipse|html<br>css<br>JavaScript|Jsp<br>struts<br>jdbc<br>mysql|[跳转](medium/preview/MED202006221530.md)|
|MED202006221531|大学生创新竞赛管理平台|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Layui|Jsp<br>servlet<br>MyBatis<br>mysql|[跳转](medium/preview/MED202006221531.md)|
|MED202006221546|校园失物招领网站|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>EasyUI|Jsp<br>Spring<br>SpringMVC<br>Hibernate<br>mysql<br>c3p0|[跳转](medium/preview/MED202006221546.md)|
|MED202103251832|云朵家教网(上门家教管理系统)|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>Spring<br>SpringMVC<br>JdbcTemplate<br>mysql<br>c3p0|[跳转](medium/preview/MED202103251832.md)|
|MED202103171416|高校毕业生就业信息管理系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>EasyUI|Jsp<br>Spring<br>SpringMVC<br>Hibernate<br>mysql<br>DBCP<br>maven|[跳转](medium/preview/MED202103171416.md)|
|MED202212081643|高校就业管理分析平台|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>Spring<br>SpringMVC<br>Hibernate<br>mysql<br>druid|[跳转](medium/preview/MED202212081643.md)|
|MED202006221537|学生管理系统|Eclipse|html<br>css<br>JavaScript|Jsp<br>SSH<br>mysql|[跳转](medium/preview/MED202006221537.md)|
|MED202006221539|传智播客网上商城|Eclipse|html<br>css<br>JavaScript|Jsp<br>SSH<br>mysql<br>c3p0|[跳转](medium/preview/MED202006221539.md)|
|MED202006221540|租车系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap<br>Apache ECharts|Jsp<br>SSH<br>mysql<br>DBCP|[跳转](medium/preview/MED202006221540.md)|
|MED202103191720|acgfan动漫主题的视频弹幕网站|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap<br>Angular<br>D3.js|Jsp<br>SSH<br>mysql<br>c3p0<br>shiro|[跳转](medium/preview/MED202103191720.md)|
|MED202006281440|家教预约系统|Eclipse|html<br>css<br>JavaScript|Jsp<br>SSH<br>mysql<br>DBCP|[跳转](medium/preview/MED202006281440.md)|
|MED202007311557|模仿天猫网站|IDEA|html<br>css<br>JavaScript<br>jQuery<br>BootStrap|Jsp<br>SSH<br>mysql|[跳转](medium/preview/MED202007311557.md)|
|MED202007311603|模仿天猫网站|IDEA|html<br>css<br>JavaScript<br>jQuery<br>BootStrap|Jsp<br>SSM<br>mysql<br>druid|[跳转](medium/preview/MED202007311603.md)|
|MED202006221542|图书馆预约占座管理系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>EasyUI|Jsp<br>SSM<br>mysql|[跳转](medium/preview/MED202006221542.md)|
|MED202006221545|学生成绩管理系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>H-ui|Jsp<br>SSM<br>mysql<br>druid|[跳转](medium/preview/MED202006221545.md)|
|MED202006221549|学生管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>c3p0|[跳转](medium/preview/MED202006221549.md)|
|MED202103151511|图书馆管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>DBCP|[跳转](medium/preview/MED202103151511.md)|
|MED202204272026|网上书店系统|IDEA|html<br>css<br>JavaScript<br>Jquery|Jsp<br>SSM<br>mysql<br>DBCP|[跳转](medium/preview/MED202204272026.md)|
|MED202007011609|学生管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>EasyUI|Jsp<br>SSM<br>mysql<br>c3p0<br>maven|[跳转](medium/preview/MED202007011609.md)|
|MED202006231304|在线考试系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>EasyUI|Jsp<br>SSM<br>mysql<br>c3p0|[跳转](medium/preview/MED202006231304.md)|
|MED202006231335|大学课程在线学习系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>c3p0|[跳转](medium/preview/MED202006231335.md)|
|MED202006281649|在线商城|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>EasyUI|Jsp<br>SSM<br>mysql<br>c3p0|[跳转](medium/preview/MED202006281649.md)|
|MED202007031411|酒店预订系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>EasyUI|Jsp<br>SSM<br>mysql<br>c3p0|[跳转](medium/preview/MED202007031411.md)|
|MED202103181916|房屋租赁系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>DBCP|[跳转](medium/preview/MED202103181916.md)|
|MED202006221929|学生选课系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap<br>Layui|Jsp<br>SSM<br>mysql<br>c3p0<br>maven|[跳转](medium/preview/MED202006221929.md)|
|MED202110051125|学生学籍管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap<br>Layui|Jsp<br>SSM<br>mysql<br>c3p0<br>maven|[跳转](medium/preview/MED202110051125.md)|
|MED202007021905|校园订餐系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>druid<br>shrio<br>lombok<br>maven|[跳转](medium/preview/MED202007021905.md)|
|MED202110042201|校园快捷订餐|IDEA|html<br>css<br>JavaScript<br>Jquery<br>H-ui|Jsp<br>SSM<br>mysql<br>druid<br>shrio<br>lombok<br>maven|[跳转](medium/preview/MED202110042201.md)|
|MED202006221550|汽车租赁管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Layui|Jsp<br>SSM<br>mysql<br>druid<br>maven|[跳转](medium/preview/MED202006221550.md)|
|MED202006231631|OA办公系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Layui<br>Bootstrap|Jsp<br>SSM<br>mysql<br>druid<br>maven<br>lombok|[跳转](medium/preview/MED202006231631.md)|
|MED202007091054|人力资源管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>DBCP<br>maven<br>spring security|[跳转](medium/preview/MED202007091054.md)|
|MED202006221552|音乐网站|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>DBCP<br>maven|[跳转](medium/preview/MED202006221552.md)|
|MED202103251838|在线音乐网站|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>DBCP|[跳转](medium/preview/MED202103251838.md)|
|MED202010140958|二手书交易系统|IDEA|html<br>css<br>JavaScript<br>Jquery|Jsp<br>SSM<br>mysql<br>c3p0<br>maven|[跳转](medium/preview/MED202010140958.md)|
|MED202103181410|毕业设计管理系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>c3p0<br>maven|[跳转](medium/preview/MED202103181410.md)|
|MED202008101923|快递代拿系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|SSM<br>mysql<br>druid<br>shiro<br>maven<br>沙箱版支付宝|[跳转](medium/preview/MED202008101923.md)|
|MED202010151839|教务管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>c3p0<br>maven<br>shiro|[跳转](medium/preview/MED202010151839.md)|
|MED202103151601|小区管理系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Velocity<br>SSM<br>mysql<br>druid<br>maven<br>shiro|[跳转](medium/preview/MED202103151601.md)|
|MED202103181447|毕业设计（论文）管理系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>AmazeUI|SSM<br>mysql<br>druid<br>maven<br>shiro<br>Ehcache|[跳转](medium/preview/MED202103181447.md)|
|MED202103221434|仿猫眼电影购票系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Layui|Jsp<br>SSM<br>mysql<br>druid<br>maven|[跳转](medium/preview/MED202103221434.md)|
|MED202103221530|敛书网电子书网站|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>druid<br>maven|[跳转](medium/preview/MED202103221530.md)|
|MED202103230935|宠物领养管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>druid<br>maven<br>lombok|[跳转](medium/preview/MED202103230935.md)|
|MED202006221554|家庭财务管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Layui<br>Apache ECharts|thymeleaf<br>SpringBoot<br>mybatis<br>mysql<br>HikariCP<br>maven|[跳转](medium/preview/MED202006221554.md)|
|MED202006221635|中小医院信息管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|thymeleaf<br>SpringBoot<br>JPA<br>mysql<br>HikariCP<br>maven<br>shiro<br>德卡D3 SDK<br>swagger|[跳转](medium/preview/MED202006221635.md)|
|MED202006291920|医院信息管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Layui|thymeleaf<br>SpringBoot<br>mybatis<br>mysql<br>druid<br>maven<br>shiro|[跳转](medium/preview/MED202006291920.md)|
|MED202006221637|齐贤易游网旅游信息管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Layui|thymeleaf<br>SpringBoot<br>mybatis<br>mysql<br>Tomcat-JDBC<br>maven|[跳转](medium/preview/MED202006221637.md)|
|MED202007031105|绩效管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>BootStrap<br>Echart|thymeleaf<br>SpringBoot<br>mybatis<br>mysql<br>druid<br>maven|[跳转](medium/preview/MED202007031105.md)|
|MED202006221942|大学教室管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|FreeMarker<br>SpringBoot<br>mybatis<br>mysql<br>druid<br>maven|[跳转](medium/preview/MED202006221942.md)|
|MED202008101913|个人博客系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Thymeleaf<br>SpringBoot<br>mybatis<br>mysql<br>druid<br>maven<br>swagger<br>Ehcache|[跳转](medium/preview/MED202008101913.md)|
|MED202103131415|迷你天猫商城|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>SpringBoot<br>mybatis<br>mysql<br>druid<br>maven|[跳转](medium/preview/MED202008101913.md)|
|MED202103151722|疫情信息管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Thymeleaf<br>SpringBoot<br>Spring Security<br>mybatis<br>mysql<br>druid<br>maven|[跳转](medium/preview/MED202103151722.md)|
|MED202103181601|EOF文件管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|SpringBoot<br>mybatis<br>mysql<br>HikariCP<br>maven|[跳转](medium/preview/MED202103181601.md)|
|MED202103221708|进销存管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>EasyUI|SpringBoot<br>mybatis<br>mysql<br>HikariCP<br>maven<br>lombok|[跳转](medium/preview/MED202103221708.md)|
|MED202103231539|舒乐美食在线分享网站|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Thymeleaf<br>SpringBoot<br>mybatis<br>mysql<br>HikariCP<br>maven|[跳转](medium/preview/MED202103231539.md)|
|MED202204272102|垃圾回收系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Layui|SpringBoot<br>mybatis<br>mysql<br>HikariCP<br>maven<br>lombok|[跳转](medium/preview/MED202204272102.md)|

### 困难(★★★★☆)[点我查看困难要求](difficult/difficult.md)
|源码编号|源码名称|编辑器|前端关键字|后端关键字|详述|
|-|-|-|-|-|-|
|DIF202006221640|黑马旅游网|IDEA|html<br>css<br>JavaScript<br>JQuery<br>Bootstrap|Jsp<br>servlet<br>jdbc<br>mysql<br>Druid<br>JdbcTemplate<br>maven<br>Redis|[跳转](difficult/preview/DIF202006221640.md)|
|DIF202012291728|计算机专业认证在线考试系统|Eclipse|html<br>css<br>JavaScript<br>Jquery<br>Bootstrap|Jsp<br>Spring<br>SpringMVC<br>Hibernate<br>mysql<br>Druid<br>Spring Security|[跳转](difficult/preview/DIF202012291728.md)|
|DIF202007021026|WePlay网上游戏商城(仿Steam)|IDEA|html<br>css<br>JavaScript<br>JQuery<br>Bootstrap|Jsp<br>SSM<br>mysql<br>DBCP<br>Redis<br>maven|[跳转](difficult/preview/DIF202007021026.md)|
|DIF202006291932|在线音乐网站|IDEA|html<br>css<br>JavaScript<br>vue<br>ElementUI|SpringBoot<br>mybatis<br>mysql<br>HikariCP<br>maven|[跳转](difficult/preview/DIF202006291932.md)|
|DIF202006291951|在线考试系统|IDEA|html<br>css<br>JavaScript<br>vue<br>ElementUI|SpringBoot<br>mybatis<br>mysql<br>druid<br>maven<br>lombok|[跳转](difficult/preview/DIF202006291951.md)|
|DIF202008171627|学生管理系统|IDEA|html<br>css<br>JavaScript<br>vue<br>ElementUI|SpringBoot<br>mybatis<br>mysql<br>druid<br>maven<br>lombok<br>shiro|[跳转](difficult/preview/DIF202008171627.md)|
|DIF202007091023|微人事|IDEA|html<br>css<br>JavaScript<br>vue<br>ElementUI|SpringBoot<br>Spring Security<br>Redis<br>RabbitMQ<br>mybatis<br>mysql<br>druid<br>maven<br>lombok<br>fastdfs<br>websocket|[跳转](difficult/preview/DIF202007091023.md)|
|DIF202103181537|问卷调查网站|IDEA|html<br>css<br>JavaScript<br>vue<br>ElementUI|SpringBoot<br>Spring Security<br>JPA<br>mysql<br>druid<br>maven<br>lombok|[跳转](difficult/preview/DIF202103181537.md)|
|DIF202103191441|校园招聘系统|IDEA|html<br>css<br>JavaScript<br>vue<br>ElementUI|SpringBoot<br>mybatis<br>mysql<br>HikariCP<br>maven|[跳转](difficult/preview/DIF202103191441.md)|
|DIF202103241009|物流管理系统|IDEA|html<br>css<br>JavaScript<br>Jquery<br>Layui|SpringBoot<br>JPA<br>mysql<br>druid<br>maven<br>swagger|[跳转](difficult/preview/DIF202103241009.md)|
|DIF202210171914|云帆培训考试系统 开源版|IDEA|html<br>css<br>JavaScript<br>vue<br>ElementUI|SpringBoot<br>mybatis<br>mybatisPlus<br>swagger<br>shiro<br>mysql<br>druid<br>maven|[跳转](difficult/preview/DIF202210171914.md)|
|DIF202210191103|风丶宇的个人博客|IDEA|html<br>css<br>JavaScript<br>vue<br>ElementUI<br>echarts|SpringBoot<br>mybatis<br>mybatisPlus<br>swagger2<br>springSecurity<br>mysql<br>HikariCP<br>maven<br>lombok<br>Redis<br>elasticsearch<br>RabbitMQ<br>MaxWell<br>Websocket|[跳转](difficult/preview/DIF202210191103.md)|
|DIF202212101509|小说精品屋|IDEA|html<br>css<br>JavaScript<br>vue<br>ElementUI|SpringBoot<br>Sharding-JDBC<br>mybatis<br>MyBatis-Plus<br>swagger2<br>springSecurity<br>mysql<br>HikariCP<br>maven<br>lombok<br>Redis<br>Caffeine<br>xxl-job<br>elasticsearch<br>RabbitMQ|[跳转](difficult/preview/DIF202212101509.md)|
|DIF202310141410|春松客服|IDEA|html<br>css<br>JavaScript<br>JQuery<br>LayUI|pug4j<br>SpringBoot<br>JPA<br>Redis<br>ActiveMQ<br>mysql<br>maven|[跳转](difficult/preview/DIF202310141410.md)|


### 专家(★★★★★)[点我查看专家要求](expert/expert.md)

|源码编号|源码名称|编辑器|前端关键字|后端关键字|详述|
|-|-|-|-|-|-|
|EXP202212101413|小说精品屋|IDEA|html<br>css<br>JavaScript<br>vue<br>ElementUI|SpringBoot<br>SpringCloud<br>nacos<br>Sentinel<br>SpringCloud Gateway<br>SpringBoot Admin<br>Sharding-JDBC<br>mybatis<br>swagger2<br>springSecurity<br>mysql<br>HikariCP<br>maven<br>lombok<br>Redis<br>elasticsearch<br>RabbitMQ|[跳转](expert/preview/EXP202212101413.md)|

## 自我介绍

我是张有路，山东大汉。

Java后端开发，7年工作经验。


## 公众号

欢迎关注我的公众号“**张有路**”，原创技术文章第一时间推送。

<center>
    <img src="http://coderzcr.gitee.io/sensor-java-picture/pictures/qrcode.gif" style="width: 100px;">
</center>


