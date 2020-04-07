---
title: 腾讯云 Layer Serverless Component 发布预告
description: "借助 scf layer 的能力，在客户部署项目时，对 node_modules 文件单独压缩。
第一次上传/或更改时，会把node_modules.zip上传到 cos 并且创建 layer 对依赖做存储。
后续再次部署时，首先对比打包的 hash 值。如果未更改则不需要重复上传，依然挂载云端的layer作为依赖。"
keywords: Serverless发布动态,Serverless发布,Serverless功能,Serverless特性
date: 2020-04-07
thumbnail: https://img.serverlesscloud.cn/202047/1586257805243-Layer%20Component.png
bannerlink: 
categories:
  -product-forecast 
useLink: 
  - 
---

### **产品介绍**：

借助 scf layer 的能力，在客户部署项目时，对 node_modules 文件单独压缩。
第一次上传/或更改时，会把node_modules.zip上传到 cos 并且创建 layer 对依赖做存储。
后续再次部署时，首先对比打包的 hash 值。如果未更改则不需要重复上传，依然挂载云端的layer作为依赖。


### **产品文档**：

敬请期待～




