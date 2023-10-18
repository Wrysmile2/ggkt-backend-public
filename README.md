# 在线点播平台

### 项目介绍

在先点播平台是一款基于微信公众号B2C模式的在线学习平台，该平台包含三大模块：直播、教学与微信消息服务；平台会定期推出直播课程，方便学员与名师之间的交流互动，学员也可以购买教学视频在线学习，分享直播与教学视频获取平台收益，平台支持直播、腾讯云视频点播、微信支付、微信授权登录、微信菜单、微信消息与腾讯云文件存储等一系列功能

### 业务流程图

![yewuliucheng](data/images/yewuliucheng.png)

### 项目技术栈

#### 后端技术

SpringBoot：简化新Spring应用的初始搭建以及开发过程

SpringCloud：基于Spring Boot实现的云原生应用开发工具，SpringCloud使用的技术：（Spring Cloud Gateway、Spring Cloud Alibaba Nacos、Spring Cloud Alibaba Sentinel、Spring Cloud Feign等）

MyBatis-Plus：持久层框架

Redis：内存缓存

RabbitMQ：消息中间件

腾讯云：文件存储

腾讯云：视频点播

欢拓云直播：直播平台

微信支付

Nginx：负载均衡

Lombok

Mysql：关系型数据库

#### 前端技术

Vue.js：web 界面的渐进式框架

Node.js： JavaScript 运行环境（版本大于16）

Axios：Axios 是一个基于 promise 的 HTTP 库

NPM：包管理器（版本大于8）

Babel：转码器

Webpack：打包工具

#### 其他技术

Docker ：容器技术

Git：代码管理工具

### 关于项目

#### 项目启动工具

Navicat15、idea、Visual Studio Code、VMware

#### 相关配置

在data中的sql文件中有全部的sql文件，在idea中连接数据库直接创建即可。

在data中有各个模块的配置文件，当启动nacos后，将配置文件配置到nacos上。

将配置文件中的一些特殊配置改成自己的信息


