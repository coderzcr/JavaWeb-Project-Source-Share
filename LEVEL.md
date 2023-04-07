# 等级说明

## 声明

我是一个Java后端，前端涉猎不多，所以该仓库中的分级主要按照后端的难度进行分级，是个人想法，可能不太准确，若有错误，请多见谅。

## 分级

本仓库中的项目难度分为5个等级，包括新手、简单、中等、困难和专家。

### 新手等级

- Java基础。
- 数据库。需要具备数据库基础，会一种数据库的基本操作（mysql、oracle、sqlserver等）及通过JDBC操作数据库。
- 前端基础（html、css、javascript）。
- 前端框架基础。选择一个主要的前端框架（bootstrap、layui、easyui等）。
- JavaEE基础。Servlet、JSP。
- Web容器（tomcat等）。

### 简单等级

在上一个等级的基础上，还需要具备如下的能力。

- 项目构建工具（maven、gradle等）。
- 基础java工具的使用（hutool、apache commons、Google Guava等）。
- 数据库连接池的使用（C3P0、DBCP、Druid、HikariCP等）。

### 中等等级

中等等级的话基本上就可以用于简单的企业应用开发了。在上一个等级的基础上，还需要具备常用的企业开发框架使用的能力。

- Web层（Struts1、Struts2、Spring MVC）。
- Service层（Spring）。
- DAO层（Hibernate、Mybatis、Spring Data JPA）。
- 模板引擎（不止jsp,还有freemarker、velocity、thymeleaf等）。

其中Spring是重中之重，而且版本非常多，推荐学习现在最流行的Springboot，使用起来非常简单，而且集成其他框架十分便捷，基本上一个jar包，一个配置就能集成。


### 困难等级

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

### 专家等级

专家等级如何分，我个人水平也达不到，还需要继续摸索。

但是个人感觉要在具备服务高性能高可用的前提下，具备分布式服务的能力。

分布式结构就是将一个完整的系统，按照业务功能，拆分成一个个独立的子系统，在分布式结构中，每个子系统被称为服务。而且这些服务能独立运行在web容器中。

- 面向服务架架构(SOA)

- 云原生技术栈
    - 容器化(docker、k8s)
    - devops
    - 微服务(基于Spring Cloud实现或istio实现)
    - serverless
---

欢迎关注我的公众号“**张有路**”，原创技术文章第一时间推送。

<center>
    <img src="http://coderzcr.gitee.io/sensor-java-picture/pictures/qrcode.gif" style="width: 100px;">
</center>
