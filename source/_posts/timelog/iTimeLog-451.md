---
title: iTimeLog 4.5.1 添加了一个时间快捷设置入口
date: 2017-12-13 09:46:33
tags: iTimeLog
---
![](http://oaaaw441f.bkt.clouddn.com/2017-12-13-timeedit.jpg "在编辑界面设置时间")

### 时间快捷修改
来自一个用户需求。

> 如方便的话，恳请作者在二个地方小调整一下，一是新建时间段能否增加一个“上一阶段结束时间为本阶段开始时间”的选项，而不是简单的直接调用当前时间

我试了一下，可能对大部分人来说，可能只有10%的时间需要在开始一个事件时间段时使用上一个阶段的结束时间，而为了这个频度的需求在每次添加时间的时候选一下，并不太方便。
所以做了一个折衷的方案，在事件编辑界面加了两个按钮，一个对开始时间进行设置，一个则针对结束时间。
开始时间的按钮，功能是把开始时间设置为上一个事件的结束时间。
结束时间的按钮，会查看是否存在下一个事件，如果存在，就设置下一个事件的开始时间，否则设置为当前的时间。
### 一个分享的bug
上一个版本，存储分享用图片时会 crash。因为苹果不同的 iOS 版本会对相册权限有不同的设置（基本上是越来越严格，越来越细致），iTimeLog 没有存储相册的权限。

### iTimeLog 4.5.0

4.5.0 没有太多可说的，就是一个快 7 年的老 app 适配了 iPhone X。
作为开发者，不得不说，积年的代码，不管有没有 bug，都会慢慢腐化。


