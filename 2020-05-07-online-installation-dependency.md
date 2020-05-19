---
title: 腾讯云云函数支持 node.js运行时安装依赖功能正式发布
description: “”
keywords: Serverless，serverless framework,node.js
date: 2020-05-09
thumbnail: 
categories:
  - product-release
useLink: 
---

### 产品背景：

如果在函数配置中启用了“在线安装依赖”，在每次上传代码后，云函数后台将检查代码包根目录的 `package.json`文件，并根据 `package.json` 中的依赖，尝试使用 npm 工具安装依赖包。

### 产品功能：
目前支持在线对 node.js运行时安装依赖

### 发布时间：
2020-05-08

### 产品文档：
https://cloud.tencent.com/document/product/583/37920