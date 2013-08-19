---
layout: post
title: "【为Octopress的Greyshade主题增加新浪微博,Instagram和Dribbble】"
date: 2013-08-16 11:47
comments: true
categories: Octopress 教程
---


Greyshade 是 Shashank Mehta 开发的一款 Octopress 的主题，简洁大方所以被广泛使用，侧栏 Social Links 部分支持很多国外社交网站，但不支持新浪微博和 Dribbble，所以我小做修改增加了这两个网站的支持。

只是修改了 `sass/parts/_header.scss` 和 `source/_includes/header.html`，增加了微博,Instagram和Dribbble 的 Icon（自己Photoshop），有需要的同学可以自取：https://github.com/qxxqxx/Greyshade


或者直接用以下命令安装主题

    $ git clone git@github.com:qxxqxx/Greyshade.git .themes/greyshade
    $ echo "\$greyshade: color;" >> sass/custom/_colors.scss
    $ rake "install[greyshade]"

修改你的 `_config.yml`，加入以下选项：

    weibo_user: qzoro # 注：新浪微博自定义网址中用户名部分或数字 ID  http://weibo.com/(此部分内容)
    dribbble_user: #填写Dribbble用户名
    instagram_user: qxxqxx #填写Instagram用户名

最后：
    
    rake generare
    rake deploy

效果见我 blog 左侧