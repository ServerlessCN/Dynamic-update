---
title: Serverless Framework Component 发布
description: "针对当前 Serverless Component 版本的优化和大版本迭代
1. 下载 cli 后，快速入门复杂，上手门槛高
2. 当前需要按照 serverless.yml的配置，在部署阶段从 npm 下载对应的 component 进行部署，影响部署效率
3. 当前的部署状态存储在本地，客户换环境或者多人协作时，状态无法保存和迁移
4. 当前的组件无法支持云端调试、日志实时输出等能力，影响开发效率"
keywords: serverless发展,Serverless 基本概念,Serverless生产力
date: 2020-03-09
thumbnail: https://img.serverlesscloud.cn/2020327/1585317553563-1578569597879-website.png  
categories:
  - product-forecast
useLink: 
  - https://github.com/serverless/roadmap-tencent/issues/325 

---
## **Serverless Framework Component 支持 灰度发布/流量切换**

2020-01-09

### **产品类型**：
新功能

### **产品背景**：
针对客户使用的问题，提供了如下优化
1. 支持检测中国用户，提供本土化的部署体验，如一键部署的交互式命令行，降低使用门槛
2. 支持 component registry，将对应 component 存储在云端的 SCF layer 中，从 layer 中下载对应的组件，提升部署速度。
3. 支持 deployment engine，将 serverless 应用的部署状态存储在云端，切换环境时也无需担心本地部署状态的丢失。
4. 支持 dev mode 命令，实时检测变化进行本地、云端的代码同步，实时输出云端日志，并且支持对 Node.js 函数进行远端调试。

### **产品解决方案/功能描述**：
针对客户使用的问题，提供了如下优化
1. 支持检测中国用户，提供本土化的部署体验，如一键部署的交互式命令行，降低使用门槛
2. 支持 component registry，将对应 component 存储在云端的 SCF layer 中，从 layer 中下载对应的组件，提升部署速度。
3. 支持 deployment engine，将 serverless 应用的部署状态存储在云端，切换环境时也无需担心本地部署状态的丢失。
4. 支持 dev mode 命令，实时检测变化进行本地、云端的代码同步，实时输出云端日志，并且支持对 Node.js 函数进行远端调试。
针对客户使用的问题，提供了如下优化
1. 支持检测中国用户，提供本土化的部署体验，如一键部署的交互式命令行，降低使用门槛
2. 支持 component registry，将对应 component 存储在云端的 SCF layer 中，从 layer 中下载对应的组件，提升部署速度。
3. 支持 deployment engine，将 serverless 应用的部署状态存储在云端，切换环境时也无需担心本地部署状态的丢失。
4. 支持 dev mode 命令，实时检测变化进行本地、云端的代码同步，实时输出云端日志，并且支持对 Node.js 函数进行远端调试。
针对客户使用的问题，提供了如下优化
1. 支持检测中国用户，提供本土化的部署体验，如一键部署的交互式命令行，降低使用门槛
2. 支持 component registry，将对应 component 存储在云端的 SCF layer 中，从 layer 中下载对应的组件，提升部署速度。


### **产品文档**：
https://github.com/serverless/roadmap-tencent/issues/325



