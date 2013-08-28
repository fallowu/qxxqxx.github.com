---
layout: post
title: "【Mac OS X双击清空废纸篓】"
date: 2013-08-28 16:47
comments: true
categories: 教程
---
<li>OS X下清空废纸篓，要么`右击，再按清空`或者`Command+Shift+delete`或者`Command+Shift+option+delete`。

<li>个人觉得太麻烦了，用`AppleScript`自己写一个小小的App放到桌面的废纸篓旁边，双击一下就能清空了。

![桌面](/images/mac-empty-the-trash-app/1.png)

代码如下：
    
    tell application "Finder"	
        empty the trash    
    end tell

或者直接下载我做好的 App
 
##[点击下载](/images/mac-empty-the-trash-app/empty.zip)

