---
layout: post
title: SPSS使用方法
date: 2008-06-25 13:45
author: vaneswh
comments: true
categories: [spss, statistics, 专业]
---
这个标题很明显的点出了——我是个标题党。
本文不涉及任何具体的操作技巧，仅仅是复习SPSS的时候总结出来的一点经验，操作环境为win+spss13.0。

0.首先对于<strong>spss中的基本操作步骤</strong>要了然于心，数据文件的建立（包括数据编码、定义变量、数据录入、数据文件的存储），数据文件的编辑（搜索变量、插入及删除变量、排序、<strong>record变量</strong>、<strong>数据文件的拆分</strong>及合并），清理数据这些基本功应掌握牢靠。
1.处理数据之前，最重要的是分析数据资料的特点。不会分析资料，也就永远不会SPSS（或者说是统计）。
2.一般来说，拿到资料，先判断其实定性资料还是定量资料。但在进行spss的时候，我建议先关注其是<strong>原始资料还是频数表资料</strong>，因为这涉及选择统计方法之前的处理。<strong>若是频数表资料，切莫忘记进行“weight cases”处理</strong>。
3.<strong>定性与定量</strong>。定性资料一般采用卡方检验，而定量资料可用t检验（单组或两组数据）、方差分析（三组及以上数据）、非参检验。
4.<strong>正态性检验</strong>。为何要进行正态性检验？因为t检验和方差分析的前提条件是资料呈正态分布，如若不满足，则要使用非参检验。进行<strong>正态性检验</strong>有2种方法，<strong>一是explore，一是one sample K-S test</strong>。（一个注意点：在两组独立样本的t检验以及方差分析中，进行正态性检验前要“split files”，<strong>检验完毕之后千万不要忘记取消“split files”</strong>）
5.t检验。主要是单一样本的t检验、配对样本的t检验和2组独立样本的t检验。具体选择那种方法要根据试验设计而定。
6.方差分析。没什么需要多讲的，如若要进行三/多组中的两组数据比较，可将变量值设为missing（此法在后面的卡方检验之R×C表中也有应用）。
7.卡方检验。对于（普通）四格表，重要是会<strong>根据资料条件看结果</strong>。T&gt;5且n&gt;40时，看Pearson Chi-square；有一格T&lt;5但n&gt;40时，看校正值Continnity Correction；n&lt;40时，用的则是Fisher确切概率法，看Fisher's Exact Test。对于配对四格表，有两种方法求解。一是corsstabs-&gt;McNemar；一是Nonparamentric-&gt;2 related samples-&gt;McNemar。至于R×C表，毋需再多言。
8.非参检验。包括配对样本、两组独立样本、多组独立样本。spss上的非参检验没有手动计算那么复杂，只需在Nonparametric菜单下寻找相应方法即可。
9.相关与回归。涉及到这一大命题最好<strong>先做散点图</strong>，看看数据的大致趋势。如用线性相关，先做正态性检验，正态用Pearson，非正态用spearman。如用多元相关及回归，则需对变量进行转换，建新变量。最后要懂得<strong>分析回归结果</strong>，<strong>方程是否有意义</strong>（由方差分析可得），<strong>根据结果列出回归方程</strong>（所以说对于基本的概念如偏回归系数、标准化偏回归系数、复相关系数、确定系数等要熟知）。
暂时写到这里，以后想起什么再做补充。
