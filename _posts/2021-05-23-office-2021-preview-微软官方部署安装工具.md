---
title: office 2021 preview 微软官方部署安装工具
date: 2021-05-23 20:30:28
cover: https://pic.imgdb.cn/item/60aa4ba52d01aeec9c4579ce.jpg
tags: 
 - office,
 - preview
 - 微软
 - 部署
---
Microsoft Office 2021是一款非常不错的办公室专用文档编辑处理工具，这款办公软件是目前使用者最多的，能够帮助用户轻松进行word文档的新建、编辑、共享以及阅读的操作。推荐使用office 2021 preview 微软官方部署安装工具安装体验最新版office 2021 preview。

![](https://pic.imgdb.cn/item/60aa4ba52d01aeec9c4579ce.jpg)

安装使用说明

1. 运行download.bat 下载最新版offcie 2021。
2. 运行install.bat安装office 2021 preview 专业增强版，包含word excel powerpoint 三合一，如果要增加组件如ACESS可在ProPlus2021Volumex64.xml中删除 <ExcludeApp ID="Access" />。

如果已下载程序安装包office，可直接运行install.bat离线安装office 2021 preview ；也可直接运行install.bat在线安装office 2021 preview 。

默认下载安装的是64位版本，若要下载安装32位版本

用文本方式打开 loadoffice2021.xml 文件将
<Add OfficeClientEdition="64" Channel="PerpetualVL2021" AllowCdnFallback="True">中的64改成32：
<Add OfficeClientEdition="32" Channel="PerpetualVL2021" AllowCdnFallback="True">

用文本方式打开 ProPlus2021Volumex64.xml 文件将
<Add OfficeClientEdition="64" Channel="PerpetualVL2021"> 中的64改成32：
<Add OfficeClientEdition="32" Channel="PerpetualVL2021">


下载地址：https://wwi.lanzoui.com/iwDkppb05ja