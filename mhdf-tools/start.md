---
description: 了解梦之工具与如何安装使用
---

# 开始

## 为什么要有 MHDF-Tools 这个插件

虽然市面上已经有同类插件了, 比如: CMI、ESS。但是他们的体验都不是特别好，ESS甚至都不支持跨服也不支持数据库存储，而CMI，虽然比ESS好一点但是一样跨服体验不是特别好，家系统也不支持跨服。而且这两个插件都特别臃肿，十分难使用。
但是有人说有HuskHome，这个插件确实支持了跨服也支持数据库存储，但是跨服体验上，用过的人都知道，有概率无法跨服，体验上不能做到特别完美。
在以上两个因素以及多个原因就有了梦之工具这个插件。

## 运行需求

1. Minecraft 1.17+
2. JDK 17+
3. Paper/Folia 及分支服务端

## 安装使用

### 单端服

1. [下载插件](https://github.com/MHDFCraft/MHDF-Tools/releases)，注意这里要下载`MHDF-Tools-Bukkit`而不是另外两个插件。
2. 将下载下来的插件文件，放入`plugins`目录。
3. 启动服务端。

### 群组服

1. 用单端服的操作将每个子服安装好梦之工具插件。
2. 为每个子服配置好`MySQL`数据库以及`Redis`数据库。
3. [下载群组端插件](https://github.com/MHDFCraft/MHDF-Tools/releases)，注意这里下载的就不是`MHDF-Tools-Bukkit`了，而是下载`MHDF-Tools-Bungee`或`MHDF-Tools-Velcity`具体下载哪个，看你到底用的哪个群组端。
4. 将下载下来的插件，放入群组端的`plugins`目录。
5. 启动服务端。

安装完插件，我们就可以开始配置插件了。