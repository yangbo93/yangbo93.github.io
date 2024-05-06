---
title: Telegram Desktop 桌面版 v2.8.5 更新限制插件使用
date: 2021-07-11 23:18:26
cover: https://pic.imgdb.cn/item/60eb0dca5132923bf81a3865.png
tags:
 - Telegram
---
  目前官方 Telegram 储存库推送了两个提交（5b2db41 和 148af59）阻止了导入表劫持注入，且不允许任何 .dll 文件放置到 Telegram 目录中。
    笔者已经测试，在 Telegram v2.8.5 beta 版本，以该原理工作的插件 Telegram-Anti-Revoke 和 FontMod 已无法使用，需要维护者进行更新修复。
    有插件需求的用户，可以暂时停留在 Telegram v2.8.4 及之前的版本使用，并等待插件更新。