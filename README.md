# Resume
**很重要：** 本人并不打算跳槽，只是看到github上的一个简历模版，忍不住回顾最近几年的成长。
简历模版链接：https://github.com/geekcompany/ResumeSample

# 联系方式
- Tel: 153****6307
- Email：baiyunchen@vip.qq.com （```QQ邮箱虽然B格低，但是随时能收到```）

---

# 个人信息

 - 白云晨/男/1993
 - 本科/[榆林学院](http://www.yulinu.edu.cn)（`全日制普通二本`）
 - 工作年限：2014年（实习）至今
 - 技术博客：http://www.cnblogs.com/baiyunchen
 - Github：https://github.com/baiyunchen
 - 当前职位：.Net开发
 - 当前薪资：你想知道的太多了
 - 工作城市：西安

---
# 个人简介
## 性格
- 热爱技术，喜欢钻研技术，敢于尝试，对.NET的发展持续关注，也非常愿意学习和了解新的语言和框架
- 热爱开源，关注开源，参与开源
- 性格开朗，喜欢与他人交流、分享

## 技能
- 熟悉面向对象思想，能熟练使用面向对象的思想进行开发
- 对`SQL SERVER`较为熟悉，能对常见SQL性能问题进行优化，简单使用过`MySQL`和`PostgreSQL`
- 了解一些大数据产品的基本特点，如`HBase`/`Solr`/`Elk Search`/`Monogo DB`/`Redis`等
- 熟悉`Jquery`/`Angular`等前端技术，也有简单尝试过`Vue`/`Avalon`等前端框架
- 熟悉`Docker`容器技术的常用命令，有基于`Docker`的持续集成实践经验，对`K8S`容器编排技术有较浅的理解，尝试在虚拟机中搭建过`K8S`集群
- 没有自己的编码风格，能遵循团队的相关编码规范，对自己所写代码的可读性要求较高
- 具备一定的文档阅读、编写能力，能根据文档快速上手第三方组件
- 有一定的`Scrum`实践经验，熟悉`Jira`/`Confluence`等常见项目管理工具

## 业务
- 对国外电商系统中的商品管理相关业务较为熟悉
- 具备较强的需求分析和理解能力
---

# 工作经历
## 新蛋信息技术（西安）有限公司 （ 2015年11月 ~ 至今 ）
### 所在项目组
```
之所以把项目组写出来，是因为新蛋是一家电商类公司，其业务是比较重的，我们在平时的工作中，也是业务为第一位。
```
#### Item Maintain Dev
  Item Matain 负责newegg集团在全球的众多在线商城的商品基础信息、价格、分类、促销、图片、库存等信息的维护，总计维护的商品数据大约在1亿5千万左右。我在该项目组的主要工作为开发、维护各类业务的UI、API，有时也会担任Scrum Master（轮值制）。
#### Architecture Member
  在我进入之后，西安分公司成立了一个架构小组，我有幸成为其中一员，主要负责将公司最新研发的各类框架、平台落地到各个项目组，并负责最新的一些技术的研究和各个兄弟团队遇到的疑难杂症的处理。
### 参与项目列表

#### Newegg Central 3.0

  	你可能会问我，为什么没有Newegg Central 2.0呢，直接上来就3.0？其实是有2.0的，只是2.0是基于AngularJS 1.X进行开发的，框架刚研发的差不多，Angular 2.0（现在都到6.X了）Pre-Release了，公司为了避免反复的迁移，就放弃了2.0，转而研发了3.0的基于Angular 2的开发。

  在这个项目中，我承担了组内核心的研发人员角色，主要负责如下内容：

- 研究Angular/TS相关技术；
- 结合组内实际业务，对公司的框架进行了二次封装，形成众多组件和公用服务；
- 在实践的过程中，逐渐摸索，为组内制定了很多Angular下的开发规范，包括代码规范、UI设计规范等等；
- 组织组员进行学习和培训，协助将公司的框架落地；
- 在落地的过程中，为框架提过N多建议，也协助框架完善过一些功能；

#### XX 小额贷款管理系统

​	该项目是新蛋为母公司联络互动做的一个小额贷款项目。在该项目中，我们团队负责项目的动态数据存储部分的API及简单的数据管理工作。

​	在该项目中，我作为我们团队内部的技术负责人，使用.Net Core 2.0 (当时还是Preview)搭建了项目的整体框架，动态数据支持使用SQL Server/MySql/HBase做数据存储，并支持数据的分布式存储。

​	在部署方面，使用Jenkins和Docker做了项目的DevOps，为项目的交付提速，得到了新蛋其他同学的好评，并在公司内部做了分享。

#### Item Restful API 维护

​	系统内对外提供数据的接口，尽量遵循Restful风格。该项目是基于公司内部API框架而建，并没有使用微软MVC等框架，整理项目架构为简单三层，实现了多语言、SQL代码可配置。

​	该项目中，主要的挑战来自于数据库数，由于数据量较大，且组内相关数据操作大部分为批量操作，所以日常代码在编写过程中，对SQL性能要求较高。

​	此外在API的开发过程中，还会涉及到一些消息队列的使用来解耦业务，还会使用一些大数据产品，如HBase/Solr等，来为数据存储、搜索服务。

#### Newegg Central 1.0

​	 新蛋集团内部的第一代平台化的管理系统产品，基于微软已经不再维护的`Sliverlight`技术，该项目我参与的程度不够深，之后就全面将平台迁移到最新的基于angular的第三代产品了，所以该项目经历不展开介绍了~

## **西安启软电子信息系统有限公司（2014年8月~2015年8月）**  

### 工作描述

​	该公司是我还未毕业时实习的一家公司，公司规模当时只有3~5人，公司主要为其他公司做电商系统的外包项目，我参与了贵州为米网农产品销售系统、陕西安惠美O2O家具销售系统等电商网站开发。

#### 安惠美家具O2O商城

​	基于著名开源项目NopCommerce商城进行的二次开发，分为手机版和Web版。开发适用于安惠美商城的UI模版。新增了套装销售功能，商品评价、运费计算、NopCommerce手机页面的访问规则。在该项目中，比较深入的学习了NopCommerce的设计，了解了EF、AutoMapper、AutoFac等工具的使用方式。

#### 为米农产品销售商城

​	该项目实现了卖家提交店铺及个人资料，经管理员审核通过后，成功入驻商城，上传商品进行销售各类农产品，并配有相关的手机版和安卓平台APP。该项目使用MVC 5 和传统3层架构，检索使用SQL SERVER全文检索。	

## 其他

### 榆林学院微信公众平台

​	在我读大学的时候（13年左右），微信公众平台刚刚起步，我就为我的母校（榆林学院）基于微信公众平台开发了查成绩、查课表、失物招领、学校新闻等各种实用性模块，该项目使用了盛派微信SDK对接微信公众平台的相关接口、使用了Html Agility Pack 爬取学校官网的相关新闻、使用MVC作为基础框架、EF为ORM框架，该项目的推出，让学校微信公众号在短短一天内暴涨8000粉丝（学校总共2W人左右），也让当时榆林学院的微信公众号在陕西省内都名列前茅。

### 业余

​	在工作之外，我也会学习一些其他的优秀开源框架和工具，比如NopCommerce、ABP、Ng.Ant.Design、ng-alain、Vue、Ocelot、Blazor等一些开源框架均有不同程度的了解，也阅读过部分项目的相关源码，尝试使用一些开源项目做一些小的Demo或者把他应用到公司项目中（上面提到的小贷API架构就参考了ABP中的不少东西）。

​	最近在学习微服务架构/DevOps的相关东西，以及K8S，希望能在不久的将来将微服务架构/DevOps和K8S应用到实际的工作中。

# 开源作品与项目

## 开源项目

- [UEditor.Core](https://github.com/baiyunchen/UEditor.Core):百度UEditor富文本编辑器后端文件上传服务，兼容.NET和.NET Core
- [NPOI.Core](https://github.com/dotnetcore/NPOI) NOPI .NET Core的迁移版本，为此项目提交过部分Bug Fixed PR，且已被合并

## 技术文章

- [MVC +WebUploader 实现分片上传大文件](https://www.cnblogs.com/baiyunchen/p/5383507.html)

- [将Dotnet Core部署到Docker上](https://www.cnblogs.com/baiyunchen/p/5812110.html)

- [尝试.Net Core—使用.Net Core + Entity FrameWork Core构建WebAPI（一）](https://www.cnblogs.com/baiyunchen/p/5665100.html)

- [微信公众平台开发概述](https://www.cnblogs.com/baiyunchen/p/5116361.html)
- [NopCommerce 3.4中商品详情页面单选框、复选框的美化](https://www.cnblogs.com/baiyunchen/p/4239259.html)



## 公开分享过的PPT

- 持续集成在小贷系统中的应用.PPTX
- 微信公众号开发

# 技能清单

- 语言：`C#`/`JavaScript`/`TypeScript`
- WEB开发：`.NET Core MVC`
- 前端技术：`Angular`/`Sliverlight`/`Vue`/`Jquery`/`Blazor`/`BootStrap`
- 数据库相关：`SQL Server`/`MySql`
- 开发工具：`Visual Studio`、`Visual Studio Code`、`Web Storm`
- 版本管理：`GIT`/`SVN`/`TFS`
- 技术框架：`Micro Service`/`ABP`/`NOP Commerce`
- 团队协作：`Scrum`
- 其他：`Docker`/`DevOps`/`Message Queue`/`Restful API`/`微信公众平台`


## 参考技能关键字

- .NET/.NET Core
- MVC
- C#
- JavaScript
- Angular
- SQL SERVER
- My SQL
- GIT
- Entity Framework
- Dapper
- Scrum
- DevOps
- Docker
- Linux

# 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。
