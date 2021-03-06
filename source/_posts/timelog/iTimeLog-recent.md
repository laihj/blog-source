---
title: 最近几个版本的iTimeLog
date: 2016-12-03 15:24:05
tags: iTimeLog
---
很久没有写 iTimeLog 的 release notes 了。最近半年也发了几个版本，4.0之后先是发了几个小版本修bug，之后开始考虑了一些新的功能。

## 搜索
iTimeLog的搜索功能是一个从 3.x 时代就一直呼声很高的功能，一直没有做是因为一直没想清楚这个功能的用处，以及把它放在哪里。设想中，iTimeLog 记录时间是为了帮助决策，我经常给别人举的例子是：记录了一个月的通勤时间之后，终于下决定搬到公司附近住，花钱省时间。最近一两年，在广州接触了一些用户之后，发现有些用户使用 iTimeLog 的目的就是记录本身，他们时不时想看看自己在某件事务上统计的时间，于是搜索统计功能对他们来说就是一个重要特性了。

![][image-1]

一开始，搜索的关键字只支持事件和类型的，后来有一天，有个用户跟我说希望能搜索事件笔记，他在广东省的各个城市之间跑来跑去，会记录坐车时间，并把出发城市和到达城市写在笔记中，如果搜索能搜到笔记中的内容，他就可能通过记录来预估交通时间了。
## 备份到 iCloud
有段时间一直想实现iTimeLog的多设备同步功能，但是同步这个事儿，坑实在太多了，只能折衷一点，把备份文件保存在云端，先解决换手机转移数据的问题。
在最近的版本中，用户可能在备份和恢复数据时选择本地或 iCloud ，如果换手机或者旧手机损坏，就可以在重新安装 iTimeLog 之后从云端拉回数据来恢复数据了。

## 3D Touch Quick Actions
在支持 3D Touch 的设备上，force touch iTimeLog 图标，弹出如图所示的快捷菜单，实现快建操作。

![点击 iTimeLog 图标][image-2]

最近几天突然想到了二级分类的使用场景（因为加了搜索），也许可能在最近几个版本实现吧。

推荐 Mac 和 iOS 的邮件客户端 [Spark][1]。

[1]:	https://sparkmailapp.com

[image-1]:	http://oaaaw441f.bkt.clouddn.com/2016-12-03-search.jpg "在bilibili上看了27小时星际迷航航海家号"
[image-2]:	http://oaaaw441f.bkt.clouddn.com/2016-12-03-touch.jpg "点击 iTimeLog 图标"

