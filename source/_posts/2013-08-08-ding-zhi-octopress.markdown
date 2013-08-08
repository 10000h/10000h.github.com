---
layout: post
title: "定制Octopress"
date: 2013-08-08 09:32
comments: true
categories: blogging
---
今后将时不时的改善自己博客界面。记录在这里吧。

首先是把首页上每篇博客头上 XX comments and XX reactions
去掉（个人觉得很丑）。这个在 {OCTOPRESS_HOME}/source/_includes/article.html。
最简单的做法就是把相关内容注释掉（html注释用 &lt; !-\- -\- &gt; ）。<!-- &lt; is < &gt; is > -->

其次是让博客中的链接在新窗口打开。

日拱一卒，不期速成。