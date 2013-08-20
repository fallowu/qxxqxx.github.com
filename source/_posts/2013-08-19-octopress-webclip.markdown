---
layout: post
title: "【Octopress的Webclip（iOS主屏幕书签）增加图标】"
date: 2013-08-19 17:16
comments: true
categories: Octopress 教程
---
##1.首先，修改`/source/_includes/head.html`
##增加
    
    <link rel="apple-touch-icon" href="/images/apple-touch-icon.png">
    
##2.然后把你的图标做成 `114*114` ，放到`/source/images/`


##3.最后
    
    rake generate
    rake deploy
    
##本Blog Webclip添加：
<li>1.直接Safari添加
<li>2.描述文件添加 （[点击这里添加](/images/octopress-webclip/add-webclip.mobileconfig)）
<!--more-->
![Safari添加](/images/octopress-webclip/safari.png)
![主屏幕效果](/images/octopress-webclip/icon.png)