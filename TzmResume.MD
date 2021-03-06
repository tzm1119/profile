# [本简历下载链接](https://github.com/tzm1119/profile/raw/master/C#-Net工作5年-唐智明简历.pdf)
# 联系方式

- 手机：15201606384（可随时联系）
- Email：657345471@qq.com 
- 微信号：tzm19921119


# 个人信息

 - 唐智明/男/1992 
 - 本科/华北电力大学热能与动力工程专业(985) /2015年毕业
 - 工作年限：5年
 - 技术博客：[https://github.com/tzm1119/profile](https://github.com/tzm1119/profile)

 - 期望职位：.Net高级程序员，架构师
 - 期望薪资：税前月薪25k~30k，特别喜欢的公司可例外
 - 期望工作位置：北京,海淀区

# 工作经历

## 北京博源恒芯科技股份有限公司 （ 2018年9月 ~ 至今 ）

### 公司网站项目 

#### 项目说明:
作为网站**架构师**，对多种前后端开发框架进行**选型**，最终选择**Vue**和**ApsNetCore**作为前后端开发框架。网站的主要功能是提供一套完整的**可变数据结构的配置文件管理**。我一开始选择使用**关系型数据库**实现这种可变的数据结构，通过多张表的组合查询，**做到了数据结构的可伸缩**。但这种方式性能较差。后来通过调查，发现使用一款开源的Json格式编辑器(json-editor)，**可以很好的解决可变数据结构的问题**。于是我对编辑器进行**改造**，增加**权限控制**，**版本管理**等功能。本项目还包含一个**统一身份认证系统**作为子项目，该系统对外提供**统一的登录服务**，与**微信登录**类似，使用**IdentityServer4框架**实现，此项目已对**多个客户端提供不同类型的身份认证服务**，**提高**了其他项目在处理**用户登录**问题的开发效率。系统开发完毕后，我对系统的使用人员进行了**培训**，培训分别对**管理员**和**普通用户**展开。对于管理员，主要培训**权限控制、版本控制、数据结构配置**。对于普通，主要培训**系统常规使用、常见问题的解决、并提供详细的使用指南**。目前上述系统均已正常运行1年，领导和同事反映系统**运行稳定，使用方便，功能灵活，易于扩展**。

#### 项目感悟

本项目**不同于**常规的**数据管理**项目，要求数据结构**可变**。如果使用传统**关系型数据库**存储数据，**性能低**，且**浪费存储空间**。而使用**json schema规则**，定义json数据结构的方式，即可提升效率，也方便用户使用。但这种方式对于**没有技术基础**的用户来说，存在一定的**困难**。因此我通过精心准备**使用指南**和**现场培训**，帮助他们度过一开始的**陌生阶段**，一旦对系统的功能有了**全面的认知**后，用户可以**自由的扩展数据结构**，**无需**开发人员参与。大大**降低沟通成本**。因此，作为开发人员，我们不仅要把代码写好，也要**考虑用户的习惯**，对较为复杂的功能，应该提供详细的**使用指南和现场培训**。

### 打印机控制系统 

#### 项目说明:

此项目为公司**核心业务**项目。整个项目**软件方面**由我**独立**完成。主要的功能点如下:**WPF/Prism界面开发**，**业务逻辑**的处理，数据**多线程**处理调度，**PLC系统联动**，通过**TCP与硬件**通信。在主要业务逻辑实现后，我对软件进行了**性能测试**。此项目要求**单PC**同时与**50个喷头**进行数据交换，因此使用**原有的多线程模型**，即每个喷头数据由**单独的线程**处理，这种方式下，需要开启**50个线程**进行数据处理。经过测试，发现线程间存在**饥饿现象**，即有些线程**长期处于挂起**状态，而我们希望**多个线程间处于一种公平**的关系。因此，我决定对上述**多线程模型加以改进**。改进后，使用**线程池**和**优先级队列**的方式，可以使用**较少的线程**，对每个喷头的数据进行**公平的处理**。**圆满**解决了上述**线程间饥饿的问题**，经过测试，**总体执行效率提升在30%左右**，开始打印时间大大缩短，平均缩短**200%**。

#### 项目感悟:

在发现软件遇到**性能瓶颈**时，首先应当找到瓶颈的**点**在哪里，然后分析问题，用**数据结构**和**操作系统**的知识来解决问题。


## 国核电力规划设计研究院 （ 2015年7月 ~ 2018年8月 ）

### 三维设计软件的二次开发

根据需求，使用**C#语言**对三维设计软件进行二次开发。

### 负责二维、三维设计软件后台数据库的管理和维护

负责数据库**创建**和数据**维护**。在管理数据库的过程中，我深入研究了**国外大型软件**的**数据库结构设计**，并翻译了大量**英文手册**。

### 主导公司内部材料编码平台的设计，编码，测试，上线

使用**Access**对编码管理数据库进行设计，然后使用**Vba**开发对应的数据处理逻辑。

# 培训经历

## 2017-3至2017-5，共3个月

在腾讯课堂参加.Net全栈开发培训，[课程链接](https://ke.qq.com/course/59314)

## 2017-6至2017-12，共7个月

在腾讯课堂参加.Net高级开发培训，[课程链接](https://ke.qq.com/course/62618#term_id=100579437)

## 2018-2至2018-12，共10个月

和jesse一起，研究AspnetCore微服务开发，[课程链接](http://video.jessetalk.cn/)

## 2018-12至2019-12，共12个月

和jesse一起，研究ASP.NET Core微服务 on K8S，[课程链接](http://video.jessetalk.cn/)

## 2019-11至2020-3，共4个月

在牛客网参加算法培训，[课程链接](https://www.nowcoder.com/courses)

## 2020-1至2020-2，共1个月

在B栈学习,redis,zookeeper,netty,k8s,[课程链接](https://www.bilibili.com/)

# 技能清单

以下均为我熟练使用的技能

- CS软件：C#/WPF/Prism框架/
- BS软件：Aspnetcore/redis/zookeeper/docker/k8s
- 前端框架：Bootstrap/Angular/Vue
- 数据库相关：SqlServer/MySQL/PgSQL/SQLite
- 版本管理、文档和自动化部署工具：Git/Svn
- 单元测试：MsTest/Xunit
- 熟悉的云平台：阿里云
      
---      
# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
      

    
    
