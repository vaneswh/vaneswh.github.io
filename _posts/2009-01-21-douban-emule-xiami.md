---
layout: post
title: 豆瓣-电驴-虾米
date: 2009-01-21 20:28
author: vaneswh
comments: true
categories: [douban, emule, xiami, 网事]
---
有一个油猴脚本叫做<a href="http://userscripts.org/scripts/show/10789">Douban Search for Resource</a>，把VeryCD和豆瓣整合到了一起。豆瓣告诉我们哪些东西好看，而VeryCD告诉我们到哪里去找这些东西。XiaMi的出现，则使得音乐资源这一块得到了进一步加强，从此，我们不必耗费自己的硬盘来拖专辑，XiaMi的服务器帮助我们满足耳朵的需求。

默认的Douban Search for Resource选择搭档的是Google、XunLei和VeryCD，想让虾米加入?打开油猴脚本管理器，编辑，找到倒数第三行，替换成<pre lang="javascript">
mySearch.innerHTML += '<a href="http://www.xiami.com/search?key=" target="_blank">'+ 'Search for ' + keyword +' in XiaMi</a>';
</pre>即可。

此外，Firefox的搜索框也可以得到加强，已经有人写出来的<a href="http://mycroft.mozdev.org/search-engines.html?name=douban">douban searchplugin</a>和<a href="http://mycroft.mozdev.org/search-engines.html?name=verycd">verycd searchplugin</a>以及我依样画葫芦出来的<a href="http://mycroft.mozdev.org/developer/devlist.html?email=vaneswh%40gmail.com">xiami searchplugin</a>(直接点击即可)。

or方法二:把以下代码保存为xiami.xml，置于firefox安装目录下的searchplugin文件夹里。
<pre lang="xml">
<?xml version="1.0" ?>
<searchPlugin xmlns="http://www.mozilla.org/2006/browser/search/">
<shortName>Xiami</shortName>
<description>Xiami</description>
<inputEncoding>UTF-8</inputEncoding>
<image width="16" height="16">
data:image/x-icon;base64,
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
</image>
<url type="text/html" method="GET" template="http://www.xiami.com/search">
<param name="key" value="{searchTerms}"/>
</url>
<searchForm>http://www.xiami.com/</searchForm>
</searchPlugin>
</pre>
至此，豆瓣啊，驴子啊，虾米啊，就在火狐狸里完美的结合成一体啦。
