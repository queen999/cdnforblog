---
title: 宽带城域网的结构
author:
	name: 覃浩
	avatar: https://cdn.jsdelivr.net/gh/queen999/ImageHosting//imagesavatar.jpg
	url: https://www.zhengyuanyuan520.com
categories: 计算机三级
date: 2020-04-13 09:46:11
comments: true
tags:  
	- 网络技术
	- 计算机三级
---

常考知识点：

宽带城域网的结构

管理和运营宽带城域网的关键技术

构建宽带城域网的基本技术与方案

网络接入技术与方法

<!-- more -->

## 宽带城域网的逻辑结构

完整的宽带城域网主要包括网络平台、业务平台、管理平台3个平台与城市宽带一个出口。

![](https://cdn.jsdelivr.net/gh/queen999/ImageHosting/images/20200413090441.png)

## 宽带城域网网络平台各层的主要功能

### 核心交换层的基本功能

- 核心交换层将多个汇聚层连接起来，为汇聚层的网络提供高速转发，为整个城域网提供一个高速、安全与具有QoS保障能力的数据传输环境。
- 核心交换层实现与主干网络的互联， 提供城市的宽带IP数据出口。
- 核心交换层提供宽带城域网的用户访问Internet所需要的路由服务。

### 汇聚层的基本功能

- 汇聚接入层的流量，进行数据分组传输的汇聚、转发与交换。
- 根据汇聚接入层的用户流量，进行本地路由、过滤、流量均衡、QoS优先级管理，以及安全控制、IP地址转换、流量整型等处理。
- 根据处理结果把用户流量转发到核心交换机或本地进行路由处理。

### 接入层的基本功能

- 接入层解决的是“最后一公里”问题。通过各种接入技术，连接最终用户，为它所覆盖范围内的用户提供访问Internet以及其它的信息服务。

### 三层结构思想

上层负责下层的数据汇聚；核心层提供出口与QoS、汇聚本地路由，接入服务用户。

## 真考试题

[单选]  下列关于宽带城域网<red>核心交换层</red>特点的描述中，<red>正确</red>的是（         ）。

A.    将多个接入层连接起来

B.    根据接入层的用户流量进行本地路由、过滤、流量均衡

C.    提供城市的宽带IP数据出口

D.    解决“最后一公里”问题

```
答案：C
解析：A选项将多个接入层连接起来的是汇聚层而不是核心交换层，故A选项错误；B选项根据接入层的用户流量进行本地路由、过滤、流量均衡的是汇聚层，故B选项错误；D选项解决“最后一公里”的是接入层的任务，故D选项错误。核心交换层实现与主干网络的互联， 提供城市的宽带IP数据出口，故C选项正确。
```

[单选]  下列关于宽带城域网<red>汇聚层</red>基本功能的描述中，<red>错误</red>的是（            ）。

A.	提供用户访问Internet所需要的路由服务

B.	根据处理结果把用户流量转发到核心交换机

C.	汇聚接入层的用户流量，进行数据转发与交换

D.	根据接入层的用户流量，进行流量均衡、安全控制等处理

```
答案：A
解析：提供用户访问Internet所需要的路由服务是核心层的基本功能，故A选项错误。
```

## 易错提示

要熟练掌握每个网络平台各层的主要功能，差异化的记忆。

![](https://cdn.jsdelivr.net/gh/queen999/ImageHosting/images/20200413094251.png)

宽带城域网网络平台的<red>核心层</red>主要承担<red>高速数据交换</red>的功能，<red>汇聚层</red>主要承担<red>路由与流量汇聚</red>的功能，<red>接入层</red>主要承担<red>用户接入与本地流量控制</red>的功能。