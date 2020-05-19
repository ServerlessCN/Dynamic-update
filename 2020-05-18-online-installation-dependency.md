---
title: 腾讯云云函数支持 node.js 运行时安装依赖功能正式发布
description: “如果在函数配置中启用了“在线安装依赖”，在每次上传代码后，云函数后台将检查代码包根目录的 `package.json`文件，并根据 `package.json` 中的依赖，尝试使用 npm 工具安装依赖包。”
keywords: Serverless，serverless framework,node.js
date: 2020-05-09
thumbnail: https://img.serverlesscloud.cn/2020519/1589851996814-%E5%9C%A8%E7%BA%BF%E5%AE%89%E8%A3%85%E4%BE%9D%E8%B5%96.png
categories:
  - product-release
useLink: 
---

### 产品背景：

如果在函数配置中启用了“在线安装依赖”，在每次上传代码后，云函数后台将检查代码包根目录的 `package.json`文件，并根据 `package.json` 中的依赖，尝试使用 npm 工具安装依赖包。

### 产品功能：
目前支持在线对 node.js 运行时安装依赖，每次更新代码后，云函数后台会自动安装依赖。

### 发布时间：
2020-05-09

### 产品文档：
https://cloud.tencent.com/document/product/583/37920
