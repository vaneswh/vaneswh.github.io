---
layout: post
title: 藏在诗中的斐波那契数列
date: 2009-11-06 20:49
author: vaneswh
comments: true
categories: [Fibonacci Numbers, mathmatics, 新知]
---
提到斐波那契数列（Fibonacci Numbers），大家肯定不会陌生：那个著名的“兔子问题”，其答案就是该数列——0,1,1,2,3,5,8,13,……

随着对结构研究的深入，人们渐渐发现，原来自然界中蕴含着如此之多的Fibonacci数列——植物的“叶序比例”、鹦鹉螺的“等角螺旋”、蜘蛛网甚至于音乐中的音阶等级[1]；更不用说与Fibonacci数列相关的黄金比率（Golden Section Numbers）[2]的应用实在是数不胜数——古希腊的帕特农神庙、纽约的联合国大厦、平常使用的信用卡的长宽比。

Saint Joseph's University的Rachel W. Hall教授，写了一本名为《跨文化的数学》的小册子，里面提到了诗歌中隐藏的Fibonacci数列[3]。

在诗歌中，韵律是由音步控制的。梵诗中的音节有两种，长音L和短音S，并且它们的比例为2:1。那么我们可以提出这样的问题：在梵诗中，如果每一行被读出来所花费的时间相等，那么我们可以做出多少个长短音节的组合呢？

假设花费一个单元时间，我们只需一个短音节S；
那么花费两个单元时间，可能的组合有SS和L；
花费三个单元时间，可能的组合有SSS、SL和LS；
如果花费四个单元时间呢？有四种组合？错！事实上，仔细想想，就会发现是五种：SSSS、SSL、LL、SLS以及LSS。
接下来不用多说，你应该看出来了，它也符合Fibonacci数列！

值得一提的是，这个规律是由生活在12世纪中期的一位叫Acarya Hemacandra的人发现的，而他比Fibonacci数列的提出者莱昂纳多早了70年......

是不是很神奇呢？其实，梵诗里还藏着另外的东西——

举个例子，我要用四个音节来作诗，那么可能的组合有

四个短音节S（SSSS）| 1种
三个短音节S和一个长音节L（LSSS,SLSS,SSLS,SSSL）| 4种
两个短音节S和两个长音节L（LLSS,LSSL,LSLS,SSLL,SLLS,SLSL）| 6种
一个短音节S和三个长音节L（SLLL,LSLL,LLSL,LLLS）| 4种
四个长音节L（LLLL）| 1种

这个数列是否也很眼熟呢？对了，这不就是鼎鼎有名的杨辉三角（国外称帕斯卡三角Pascal's Triangle）中的一行吗？

<embed width="386" height="166" menu="false" quality="high" src="http://f.yupoo.com/v.swf?id=vaneswh-ff8080812626f3d7012632bfbf6f735a-m" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer" ></embed>

而这个发现，据说是由生活在公元前200年的Pingala完成的，哦买噶，怎么这么多奇人异士啊~~
————————————————————
注释:
[1]许多民族音乐采用五度音阶，自然音乐采用八度音阶，而古典音乐和当代音乐则采用十三度音阶。援引自《数学——描绘自然与社会的有力模式》。
[2]如果我们成对地抽取Fibonacci数列中连续的数，它们的比值将越来越接近黄金比率。
[3]下文的例子译自R.Knott教授收集的<a href="http://www.maths.surrey.ac.uk/hosted-sites/R.Knott/Fibonacci/fibInArt.html">资料</a>，因为感觉他的版本更易理解。
