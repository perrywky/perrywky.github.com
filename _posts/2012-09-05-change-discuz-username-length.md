---
layout: post
title: 修改discuz用户名的长度限制
categories:
- xd.com
tags:
- discuz
- github
---

Discuz的用户名最长只有15位，不能满足xd.com的需求，为了增加长度，需要将很多表里的用户名字段都做调整，我google了一下，发现已经有人做了[统计](http://www.oicto.com/ucenter-discuz-username-15/)，针对的是center 1.6.0和discuz x2.0版本，但是他的列表并不完全，我补充了一些漏掉的字段，并写了两个程序来完成更新：

[ucenter](https://gist.github.com/3632682)
[discuz](https://gist.github.com/3634492)

如果你是直接使用discuz的注册页面，你也需要对程序做些修改，[这里](http://www.oicto.com/ucenter%E5%92%8Cdiscuz-x2%E4%BF%AE%E6%94%B9%E6%B3%A8%E5%86%8C%E7%94%A8%E6%88%B7%E5%90%8D%E9%95%BF%E5%BA%A6%E9%99%90%E5%88%B6php%E7%A8%8B%E5%BA%8F%E5%92%8C%E6%95%B0%E6%8D%AE%E5%BA%93%E4%BF%AE%E6%94%B9/)有做介绍。
