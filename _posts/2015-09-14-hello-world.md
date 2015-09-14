---
layout: post
title: "Hello World"
description: ""
category: 
tags: []
---
{% include JB/setup %}

#### 2.2 Git基础--记录每次更新到仓库

###### 原文：

[Git基础--记录每次更新到仓库](http://git-scm.com/book/zh/v2/Git-基础-记录每次更新到仓库)

###### 命令：

	git status

*文件的状态变化周期*	
![文件的状态变化周期](http://7xlsex.com1.z0.glb.clouddn.com/progitQQ20150914-1@2x.jpg)

#### 2.3 Git基础--查看提交历史

###### 原文：

[Git基础--查看提交历史](http://git-scm.com/book/zh/v2/Git-基础-查看提交历史)

###### 命令：
    
    git log

默认不用任何参数的话，git log 会按提交时间列出所有的更新，最近的更新排在最上面。

######常用选项：

* -p	用来显示每次提交的内容差异。
* --stat	每次提交的简略的统计信息。
* -(n)	仅显示最近的 n 条提交。
* --since, --after	仅显示指定时间之后的提交。
* --until, --before		仅显示指定时间之前的提交。
* --author	仅显示指定作者相关的提交。
* --committer	仅显示指定提交者相关的提交。

###### 作者与提交者

* 作者： 实际作出修改的人。
* 提交者： 最后将此工作成果提交到仓库的人。
 

















