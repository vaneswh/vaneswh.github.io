---
layout: post
title: 在iPod Touch上享受TED
date: 2010-05-16 12:28
author: vaneswh
comments: true
categories: [ipod touch, mp4te, ted, 新知]
---
本篇教学目的：制作带（多轨）字幕的、适于iPod Touch/iPhone播放的TED视频。

所需材料及工具：原生TED视频、匹配的SRT/SMI字幕、MP4TE

具体步骤：

<strong>1.获取TED视频</strong>
这个有很多方法，可以直接在<a href="http://www.ted.com">TED网站</a>上下载，可以用Firefox+<a href="http://www.downloadhelper.net/">DownloadHelper</a>在Youtube上的<a href="http://www.youtube.com/user/TEDtalksDirector">TED频道</a>下载。当然，如果你不想做太多人工工作，可以直接用iTunes或类似的Podcast订阅工具订阅<a href="itpc://52podcast.com/ted/?feed=rss2">这个地址</a>，就可以自动获取最新/所有视频了。在这里要特别感谢<a href="http://52podcast.com/">52podcast</a>提供避难所，由于众所周知的原因，TED的官方RSS已经失效。

<strong>2.获取相匹配的字幕</strong>
TED官方网站的视频可加载字幕，也提供transcript，但不提供字幕的下载。这里介绍<a href="http://diyism.com/?action=tool.ted_srt">一个网址</a>，把TED视频地址贴上去，可自动获取该视频的字幕文件（SRT格式）。如果大家有什么其他方法获取字幕，也欢迎留言提供。

<strong>3.使用MP4TE制作含字幕视频</strong>
在<a href="http://www.bomijoa.com/?document_srl=146">此处</a>下载MP4TE0.5.4（最新版，支持添加多轨字幕），安装（需要.NET Framework 3.5）。但因为这个版本有些bug，所以安装好后还需<a href="https://docs.google.com/leaf?id=0B9XvpH5HXfR9Y2NkOTVmZDMtYjUyZS00ZWVkLTgyYmQtZGQ5NDQ4NTE5MDE1&hl=en">下载</a>mp4box.exe这个文件，解压后复制到安装目录下的tools文件夹替换原来文件。

打开MP4TE，把待处理的文件（支持MP4/AVI格式）拖进处理框。如果字幕和视频在同个文件夹下，软件会自动添加。
<a href="http://www.yupoo.com/photos/vaneswh/74577517/" title="1"><img src="http://pic.yupoo.com/vaneswh/88213952e738/medium.jpg" alt="1" width="500" height="345" border="0" /></a>

双击文件名，弹出设置框，把字幕（支持SRT/SMI格式）拖进字幕处理框，指定字幕的语言、字体等，设置完毕后点Apply，然后OK。
<a href="http://www.yupoo.com/photos/vaneswh/74577518/" title="2"><img src="http://pic.yupoo.com/vaneswh/01640952e73a/medium.jpg" alt="2" width="500" height="350" border="0" /></a>

返回主界面，设置输出文件夹、文件名等，点Batch Generate，大功告成！

<strong>4.用iTunes同步</strong>
这样一来就可以美美的享受TED啦，这对我等英语不那么溜的同学来讲，真是天大的福音啊～
