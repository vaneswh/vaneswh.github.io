---
layout: post
title: Google Toolbar里的StumbleUopn!
date: 2008-10-02 14:42
author: vaneswh
comments: true
categories: [google, stumbleupon, 分享]
---
昨日在<a href="http://www.downloadsquad.com/2008/10/01/stumbleupon-relaunches-no-browser-toolbar-necessary/">Download Squad</a>里看到StumbleUpon发布了Web版toolbar的消息：现在用户无需安装stumblupon的工具栏，只要在地址栏中键入www.stumbleupon.com/toolbar，即可浏览神奇的stumbleupon世界（但是无法使用收藏功能）。
其实这也不是什么新消息了，早前我就从某位国外blogger那里发现了<a href="http://www.doushite.org/blog/2008/02/%e4%b8%8d%e5%ae%89%e8%a3%85%e5%b7%a5%e5%85%b7%e6%a0%8f%ef%bc%8c%e7%85%a7%e6%a0%b7%e4%bd%bf%e7%94%a8stumbleupon/">stumbleupon的小秘密</a>，只不过那时起用的地址是www.stumbleupon.com/demo（现在该地址尚未失效）。
曾经有一段时间我重度依赖stumbleupon来打发我的闲暇时光，那时stumbleupon的工具栏是我FF里必不可少的插件之一。大半年过去了，我的热情在慢慢消退，同时也没有大把的时间来挥霍，所以逐渐远离了它。但我还是不得不说，偶尔上上这个网站，真能淘到不少精彩有用的资源。
StumbleUpon官方的工具栏实在臃肿，而我也用不了那许多功能；既然如今有了替代的方法，直接收藏web版工具栏的地址就可以搞定；不过我向来喜欢折腾，因为在FF里为了节省空间，我从来不显示书签工具栏，如今为了一个stumbleupon的地址，就要多占用一行，岂不是得不偿失?
最后我把希望寄托在Google Toolbar上，找到<a href="http://www.google.com/tools/toolbar/buttons/intl/zh-CN/apis/howto_guide.html">自定义按钮的API说明</a>，开始造按钮。由于我的目的只是想把按钮当作一个书签，所以过程很简单：
1.首先确保安装了Google Toolbar；
2.打开stumbleupon首页，在其搜索框处右击——&gt;生成自定义搜索，Google工具栏里就会出现一个SU的favicon图标，此时点击它就会来到SU首页；
3.但我的目标路径不是首页，欲改之，打开工具栏选项——按钮——stumbleupon——修改——使用高级编辑器，把内的地址改为www.stumbleupon.com/toolbar，最后保存即可。
<a title="Flickr 上 vaneshi 的 google-t-1" href="http://www.flickr.com/photos/vaneswh/2906890448/"><img src="http://farm4.static.flickr.com/3066/2906890448_edb09c4770.jpg" alt="google-t-1" width="500" height="311" /></a>
<a title="Flickr 上 vaneshi 的 google-t-2" href="http://www.flickr.com/photos/vaneswh/2906046187/"><img src="http://farm4.static.flickr.com/3119/2906046187_28b849db0c_o.jpg" alt="google-t-2" width="379" height="293" /></a>
<a title="Flickr 上 vaneshi 的 google-t-3" href="http://www.flickr.com/photos/vaneswh/2906890744/"><img class="alignnone" src="http://farm4.static.flickr.com/3118/2906890744_d36ea711cf.jpg" alt="google-t-3" width="500" height="351" /></a>
Google Toolbar真是个好东西，利用它可以做出一系列按钮，即时获取一些常用网站的更新信息，很好很强大:)
