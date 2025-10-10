<p align="center">
<a href="https://github.com/coderzcr/JavaWeb-Project-Source-Share" target="_blank">
	<img src="public/oldPicturesFromGitee/zcr's blog.png" width="30%"/>
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

### 难度等级说明

本仓库中的项目难度分为5个等级，包括新手、简单、中等、困难和专家。

我是Java后端，前端涉猎不多，所以该仓库中的分级主要按照后端的难度进行分级，可能不太准确，请多见谅。

### 新手(★☆☆☆☆)[点我查看新手项目](newcomer/newcomer.md)
- **适合人群**：Java基础入门，了解基本SQL语法的初学者
- **技术特点**：主要使用JSP+Servlet+jdbc+mysql实现，项目结构简单，适合初学者上手
- **学习目标**：了解Web项目基本结构，掌握Servlet开发基础，学习数据库操作

### 简单(★★☆☆☆)[点我查看简单项目](easy/easy.md)
- **适合人群**：掌握基础JavaWeb开发，了解连接池技术的学习者
- **技术特点**：在新手基础上增加了数据库连接池(c3p0、DBCP等)，部分项目使用maven管理
- **学习目标**：学习数据库连接池使用，理解项目优化思想，掌握maven基本使用

### 中等(★★★☆☆)[点我查看中等项目](medium/medium.md)
- **适合人群**：熟悉JavaWeb开发，想学习主流框架的开发者
- **技术特点**：主要使用SSH、SSM、SpringBoot等主流框架，包含权限控制、缓存等功能
- **学习目标**：掌握主流框架使用，理解分层架构设计，学习企业级开发模式

### 困难(★★★★☆)[点我查看困难项目](difficult/difficult.md)
- **适合人群**：有一定项目经验，想提升技术深度的开发者
- **技术特点**：前后端分离架构(Vue+ElementUI)，使用Redis缓存，消息队列等中间件
- **学习目标**：掌握前后端分离开发，学习分布式缓存，理解高并发场景处理

### 专家(★★★★★)[点我查看专家项目](expert/expert.md)
- **适合人群**：有丰富项目经验，想学习微服务架构的高级开发者
- **技术特点**：基于SpringCloud的微服务架构，包含服务注册发现、网关、熔断等组件
- **学习目标**：掌握微服务架构设计，理解分布式系统原理，学习云原生技术

## 自我介绍

我是张有路，山东大汉。

Java后端开发，9年工作经验。


## 公众号

欢迎关注我的公众号“**张有路**”，原创技术文章第一时间推送。

<center>
    <img src="public/oldPicturesFromGitee/qrcode.gif" style="width: 100px;">
</center>


