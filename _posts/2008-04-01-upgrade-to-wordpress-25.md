---
layout: post
title: 成功升级到wordpress2.5
date: 2008-04-01 16:29
author: vaneswh
comments: true
categories: [wordpress, 日常]
---
的确有很大的改进。
除了更美观之外，操作性也上了一个层次。
离我理想中的后台又近了一步。
PS：这是第一次进行升级操作，在这里做一点笔记。
首先备份数据库、.htaccess、sitemap.xml、sitemap.xml.gz、wp-config.php；
然后禁用所有插件；
接着删除除wp-content、wp-images、wp-includes/languages/文件夹以外的所有文件（wp-content/cache和wp-content/plugins/widgets也要删，不过由于我是第一次升级，所以没有这两个文件夹）；
接着上传更新的安装包，在浏览器中打开http://example.com/wp-admin/upgrade.php进行升级，稍等片刻至更新完成。
