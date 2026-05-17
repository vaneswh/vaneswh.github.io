---
layout: post
title: WP Greet Box跨平台,变身Blogger Greet Box
date: 2009-07-06 19:59
author: vaneswh
comments: true
categories: [blogger-tips, 分享]
---
折腾WordPress的同仁多多少少都应该听说过WP Greet Box这个插件吧?它能根据来访者的进入链接，显示不同的欢迎辞，顺带可以推荐RSS订阅以及显示相关文章，算是一个优化读者体验的插件，虽然实际作用也许并不大。
现在，BlogSpot上的朋友也可以实现这一“花瓶”功能，根据就是<a href="http://classictutorials.blogspot.com/2009/04/wp-greet-box-plugin-for-blogger-blogger.html">Classic Toturials</a>放出的一个Hack。安装步骤异常简单：
1.复制以下代码
<pre lang="javascript">
<script src="http://kaushik259106.googlepages.com/TextToBeDisplayedDiv.js" type="text/javascript">
</script>
<div id="mainDisplayDiv" style="background:#F8F8FF;border:1px solid  #B6AFA9;display:none">
<div id="dynamicContentDisplayed">
</div>
<script type="text/javascript">
// Give your feed url here
var feedURL = "http://feeds2.feedburner.com/blogspot/ct";
var dynamicHTMLText = displayRequiredText(feedURL);
document.getElementById("dynamicContentDisplayed").innerHTML
= dynamicHTMLText;
</script>
</div>
<script src="http://kaushik259106.googlepages.com/HideShowDiv.js" type="text/javascript">
</script>
<script type="text/javascript">
//List your domains where you dont want to show up. Suppose
//when people navigate within your site and you dont want to
// show up. This is , seperated
var myRestrictedDomainList = "classictutorials.blogspot";
showHideDiv(myRestrictedDomainList);
</script>
</pre>
2.找到var feedURL这一行，把引号里的地址换成自己blog的RSS地址；找到var myRestrictedDomainList这一行，把引号里的地址换成自己的blog地址——这是为了避免当别人在你的blog内游逛时，时不时地跳出Greet Box烦人家。
3.在blogger后台--Layout--Edit Html选项中，把上述修改过的代码copy至[/head]之前。
So,That's done.

不过需要说明的是，此Blogger Greet Box目前只支持Google、Yahoo、Digg、Stumbleupon四个站点；另外友情提醒：此hack中的核心文件——代码中出现的那两个js文件是存放在即将歇业的Google Page里的，担心其安全的朋友最好另寻佳处安置:)
