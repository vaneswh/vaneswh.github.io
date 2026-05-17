---
layout: post
title: 用EasyPHP在本地搭建WordPress
date: 2008-07-14 11:21
author: vaneswh
comments: true
categories: [tips, wordpress, 分享]
---
搭建本地wordpress想必大多数人用XAMPP吧，但我用EasyPHP只是因为它体积稍小，下载的时候先“叮---”了。
使用方法很简单，和XAMPP一个套路。
Step1.在官方网站下载EasyPHP程序，安装至某盘。
Step2.运行easyphp，需要注意的是<strong>如果有应用程序占用了80端口，Apache是无法启动的</strong>。首先可设置软件界面为中文，点击左边E型小图标--&gt;configuration--&gt;easyphp--&gt;language--&gt;简体中文。
<a href="http://www.flickr.com/photos/vaneswh/2666699096/"><img style="vertical-align: middle;" src="http://farm4.static.flickr.com/3163/2666699096_0df3faae79_o.jpg" alt="" width="429" height="70" /></a>
在浏览器地址栏中输入<strong>http://127.0.0.1/home</strong>，即可打开<strong>管理界面</strong>，如图所示：
<a href="http://www.flickr.com/photos/vaneswh/2665875419/"><img style="vertical-align: middle;" src="http://farm4.static.flickr.com/3104/2665875419_b10a142bca.jpg" alt="" width="500" height="293" /></a>
点击相应的链接进行具体操作。
比如要管理数据库，点击mysql manager，来到phpmyadmin管理界面，在create new database处新建一个数据库命名为wp。
Step3.下载wordpress安装包，解压成wordpress文件夹，放在easyphp安装文件夹下的www文件夹下。修改wp-config-sample.php（最后重命名为wp-config.php），数据库名填wp，默认用户名root，密码为空（如果要改用户名和密码，先在phpmyadmin的Privileges处新建用户名及密码）。
Step4.在浏览器地址栏输入<strong>http://127.0.0.1</strong>，看到wordpress文件夹，点进去，开始安装wordpress，后面步骤省略。
（完）
