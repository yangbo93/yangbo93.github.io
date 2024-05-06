---
title: 微软升级了DirectML支持的Pytorch版本
date: 2022-12-10 21:16:16
cover: https://pic.imgdb.cn/item/63948951b1fccdcd36014680.jpg
categories: 网络
tags:
 - Github
---
昨日，微软低调更新了其Github项目DirectML。
更新主要将pytorch-directml支持的pytorch版本更新到1.13.0，并增加了对Python3.10和3.9的支持。
![](https://pic.imgdb.cn/item/63948951b1fccdcd36014680.jpg)
因为前段时间Novel AI模型的泄漏和Stable-Diffusion的爆火，Direct ML项目受到了更多的关注。
DirectML的主要功能是可以让没有配备N卡但支持Direct X12的任意Windows10设备享受AI计算时的GPU加速。对没钱买N卡但想要体验AI绘图的用户来说是一个好消息。
![](https://pic.imgdb.cn/item/639489b0b1fccdcd3601cc9b.jpg)
目前，Stable-Diffusion方面暂未表明是否会跟进支持新版DirectML。但此前曾明确表示因为DirectML支持的Pytorch和Python版本太低，不会增加对其的支持。