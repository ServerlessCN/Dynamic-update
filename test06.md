---
title: Serverless Framework Component 变更下线
description: 当前北京竹间、江娱互动、腾讯视频等多家客户对于灰度发布能力有诉求。希望 Serverless 应用可以支持灰度发布、不同版本之间流量切换的能力
keywords: serverless发展,Serverless 基本概念,Serverless生产力
date: 2020-01-09
thumbnail:  
categories:
  - change-offline
useLink: 
md: test06
---
## **Serverless Framework Component 变更下线**

2020-01-09

### **变更执行时间**：
2020-09-02

### **产品变更内容**：

当前北京竹间、江娱互动、腾讯视频等多家客户对于灰度发布能力有诉求。希望 Serverless 应用可以支持灰度发布、不同版本之间流量切换的能力

### **替代方案**：
通过在 serverless.yml 中支持流量切换的配置项，支持客户方便的使用灰度发布能力。
允许客户配置完成后，流量在两个版本之间进行按比例的分发，从而实现灰度发布的能力和回滚的能力。


