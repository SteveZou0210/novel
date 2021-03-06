# 小说精品屋




#### 项目介绍

小说精品屋是一个多端（PC、WAP）阅读、功能完善的原创文学CMS系统，由前台门户系统、作家后台管理系统、平台后台管理系统、爬虫管理系统等多个子系统构成，支持会员充值、订阅模式、新闻发布和实时统计报表等功能。

小说精品屋-plus重新进行了数据库设计、代码重构和功能增强，提升了程序整体的可读性和性能，增加了很多商用特性。主要升级如下：

- [x] 数据库重新设计，结构调整。
- [x] 服务端代码重构，MyBatis3升级为MyBatis3DynamicSql。
- [x] 移动站与PC站站点分离，浏览器自动识别跳转。
- [x] PC站UI更新。
- [x] 支持前端模版自定义，内置多套模版。
- [x] 新闻模块。
- [x] 排行榜。
- [x] 小说评论模块。
- [x] 阅读主题模块。
- [x] 作家专区。
- [x] 充值。
- [x] 订阅。
- [x] 后台管理系统。
- [x] 爬虫管理系统。

#### 项目结构

```
novel-plus -- 父工程
├── novel-common -- 通用模块
├── novel-front -- 前台门户&作家后台管理子系统（可拆分）
├── novel-crawl -- 爬虫管理子系统
├── novel-admin -- 平台后台管理子系统
└── templates -- 前端模版
```

#### 技术选型

| 技术                 | 说明                                                         
| -------------------- | ---------------------------
| SpringBoot           | Spring应用快速开发脚手架     
| MyBatis              | 持久层ORM框架 
| MyBatis Dynamic SQL  | Mybatis动态sql
| PageHelper           | MyBatis分页插件
| MyBatisGenerator     | 持久层代码生成插件
| Sharding-Jdbc        | 代码层分库分表中间件
| JJWT                 | JWT登录支持  
| SpringSecurity       | 安全框架                           
| Shiro                | 安全框架  
| Ehcache              | Java进程内缓存框架(默认缓存)  
| Redis                | 分布式缓存(缓存替换方案，默认关闭，一行配置开启)                               
| ElasticSearch        | 搜索引擎(搜索增强方案，默认关闭，一行配置开启)                      
| RabbitMq             | 消息队列(流量削峰，默认关闭，一行配置开启)  
| OSS                  | 阿里云对象存储服务(图片存储方式之一，一行配置即可切换) 
| FastDfs              |开源轻量级分布式文件系统(图片存储方式之一，一行配置即可切换)                      
| Redisson             | 实现分布式锁                                       
| Lombok               | 简化对象封装工具                                                                               
| Docker               | 应用容器引擎   
| Mysql                | 数据库服务   
| Thymeleaf            | 模板引擎     
| Layui                | 前端UI                    
                 

#### 开发工具
感谢Jetbrains公司提供的免费License。

[![index]( https://s3.ax1x.com/2021/01/14/sdHsJg.png )]( https://www.jetbrains.com/?from=小说精品屋)


#### 接口文档

[点击查看接口文档示例](doc/api/api.md)

#### 橙色主题模版截图
##### PC站截图

1. 首页

![img](https://s3.ax1x.com/2020/12/27/r5400A.png)

2. 分类索引页

![img](https://oscimg.oschina.net/oscnet/up-d0b2e03129bfae47b8bb96a491b73d383c5.png)

3. 搜索页

![img](https://s3.ax1x.com/2020/12/27/r5TO8x.png)

![img](https://oscimg.oschina.net/oscnet/up-ed5f689557718924acac76bc3ebca36afcb.png)

4. 排行榜

![img](https://oscimg.oschina.net/oscnet/up-78d5a68586cd92a86c669311f414508f922.png)

5. 详情页

![img](https://oscimg.oschina.net/oscnet/up-8be2495a2869f93626b0c9c1df6f329747a.png)

6. 阅读页

![img](https://oscimg.oschina.net/oscnet/up-517c84148d2db8e11717a8bbecc57fa1be7.png)

7. 用户中心

![img](https://oscimg.oschina.net/oscnet/up-805a30e7a663a3fd5cb39a7ea26bc132a01.png)

8. 充值

![img](https://oscimg.oschina.net/oscnet/up-5a601b0b3af3224d0bebcfe12fc15075d34.png)

![img](https://oscimg.oschina.net/oscnet/up-face25d02c07b05b2ce954cc4bf4ee6a0cc.png)

9. 作家专区

![img](https://oscimg.oschina.net/oscnet/up-30766372cc7f56480ff1d7d55198204f6ea.png)

![img](https://s3.ax1x.com/2020/11/17/DVFiQI.png)

![img](https://s1.ax1x.com/2020/11/09/B7X5oF.png)

![img](https://s1.ax1x.com/2020/11/09/B7XLsx.png)

10. 购买

![img](https://oscimg.oschina.net/oscnet/up-ce0f585efd82a9670335f118cf5897c85e9.png)

![img](https://oscimg.oschina.net/oscnet/up-f849960f4c1303fea77d26e64fc505a7180.png)

##### 手机站截图

1. 首页

   <img src="https://s3.ax1x.com/2020/12/27/r5447n.jpg" alt="index" width="300" />

2. 小说列表页

   <img src="https://s3.ax1x.com/2020/12/27/r55xKg.jpg" alt="微信图片_20190904181558" width="300" />

3. 小说详情页

   <img src="https://s3.ax1x.com/2020/12/28/roZWOf.jpg" alt="QQ图片20191018161901" width="300" />

4. 小说阅读页

   <img src="https://s3.ax1x.com/2020/12/27/r55Stx.jpg" alt="QQ图片20191018161901" width="300" />

##### 爬虫管理系统截图

![img](https://s1.ax1x.com/2020/11/03/BsOgbD.png)

![img](https://s1.ax1x.com/2020/11/03/BsOHr8.png)

##### 后台管理系统截图

![img](https://oscimg.oschina.net/oscnet/up-0552343538674a22a64819834100558f39b.png)

![img](https://s3.ax1x.com/2020/12/01/DWgLNT.png)

![img](https://s3.ax1x.com/2020/12/01/DfmRCd.png)

![img](https://oscimg.oschina.net/oscnet/up-faf5dda7320674c29a1772bc0c81d74762e.png)

#### 深色主题模版截图
##### PC站截图

1. 首页

   ![index](https://static.oschina.net/uploads/img/202006/24151811_wIus.png)

##### 手机站截图
1. 首页

   ![index](https://static.oschina.net/uploads/img/202006/24151812_OOob.jpg)

4. 小说详情页

   ![微信图片_20190904181558](https://static.oschina.net/uploads/img/202006/24151812_ZosF.png)

5. 目录页

   ![QQ图片20191018161901](https://static.oschina.net/uploads/img/202006/24151812_Krva.png)

5. 小说阅读页

   ![QQ图片20191018161901](https://static.oschina.net/uploads/img/202006/24151813_fDgT.png)

#### 蓝色主题模版截图（更新中）

   ![QQ图片20191018161901](https://s3.ax1x.com/2020/12/27/r5Fe0A.png)


