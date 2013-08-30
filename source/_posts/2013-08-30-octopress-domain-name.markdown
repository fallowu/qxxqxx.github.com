---
layout: post
title: "【自定义 Octopress 域名】"
date: 2013-08-30 14:56
comments: true
categories: Octopress 教程
---
<li>在Github上搭建Octopress Blog，是完全免费的，但是缺点就是网址固定`github's username.github.io`
<li>当然也有许多的免费顶级域名，例如：`.tk` 新的 `.ml` `.ga` 等等……
<li>但是我还是喜欢`.com`，所以买了一个：<http://qxxqxx.com>

<br/>1. 首先，你要注册一个域名……这个就不多说了，自己Google去吧。

2.在`/source`里面，创建一个名为`CNAME`的无后缀文本，在里面填写你自己注册的域名。

![CNAME](/images/octopress-domain-name/1.png)

3.修改`_config.yml`，把第一行的`url`修改为你注册的域名。

![CNAME](/images/octopress-domain-name/2.png)

最后：
    $ rake generate
    $ rake deploy