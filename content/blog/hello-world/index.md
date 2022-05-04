---
title: Hello World, Hello Covid 19
date: "2022-05-04T06:20:51.265Z"
description: "这绝对是最后一个博客站了"
---

今天是小区封闭第 46 天，五一假期第 4 天。

过去建过多次博客站，尝试过多种技术栈（Gatsby、原生 React、.html + .md + .sh/.js 编译脚本<sup>[ 1 ](#1)</sup>）、多种部署方式（gh-pages、腾讯云 - 静态网站托管），也用过 Github Issues<sup>[ 2 ](#2)</sup>，最后都因为各种各样的原因半途而废了。

其中，.html + .md + .sh 编译脚本 + 腾讯云 - 静态网站托管<sup>[ 1 ](#1)</sup>的方案算是完成度相对比较高的了，放了一些关于 git 和 vim 的小文章。后来还是没坚持下来，一方面是因为页面实在不知道怎么设计，一方面是因为腾讯云的控制台实在太难用了。

用 Github Issues<sup>[ 2 ](#2)</sup> 承载的是比较早期的一些内容，学习笔记为主，主要是 2018 - 2019 年这段时间产出的，2020 - 2021 年生活上的变动比较多，也没怎么写东西。这套方案其实对于纯放文章来讲足够了，就是比较难支持一些定制化的内容，还是独立的站点更自由一些。

除博客站外，在掘金、Medium 也有零星产出。

整体来讲，过去几次博客半途而废的原因可以归纳为以下几点：

1. 缺少反馈：年访问量只有个位数，监控台上获取的访问数据全都是自己测试控制台 o 不 ok 而访问的。现在这个年代可能是对个人博客不太友好了，内容的产出越来越集中到大的平台，中文圈比如公众号、掘金、知乎。英文圈的情况似乎好一点，而且经常能发现被精心维护的个人博客。

没有就没有吧，阅读量高起来的当然好，没人看就当是自己的知识积累存档和写作练习处吧。毕竟知识总要积累，写作也是必备的技能。

另外就是考虑在成熟的平台上往博客引流，例如 Twitter、脉脉等等。

2. 页面丑陋：所以这次用了和 [Overreacted](https://overreacted.io/) 一样的 Gatsby 脚手架（[gatsby-starter-blog](https://github.com/gatsbyjs/gatsby-starter-blog)）（甚至连部署也放到了 Gatsby Cloud）。一站式的体验还是很赞的👍。

不过既然号称是「前端工程师」，对页面设计有点 sense 还是好的。后面准备这方面多看看，提升一下。

3. 没有内容：实在不知道写些什么。技术类的文章几乎已经没有什么空白领域了，所有的内容在 Google 上随便搜搜都能看到从各种角度写的不同文章。

有就有吧，我写管我写。刚才研究了一下一个域名配置了多条 A 记录会怎么样，下次写一下。其实写作是一次和自己的对话，对于知识类的文章，写出来可以帮自己梳理整体架构，能写得明白说明是真的弄懂了。

这次长期在家办公加五一假期，空闲时间决定重新来做这件事情。
现在的站点架构，可以实现<del>提交 PR 并合并</del><sub>太麻烦了，我懒得弄 PR</sub>推送到 master 之后即可自动打包构建部署，基本没什么麻烦事了。
花点时间把解析、SSL 也弄好了。现在是域名、DNS 解析、SSL 在腾讯云，部署在 Gastby Cloud。
<span onMouseOver="this.style.background='white'" onMouseOut="this.style.background='var(--color-text)'" style="background: 'var(--color-text)'">（Gastby Cloud 老是获取不到我在腾讯云上配的 DNS 的状态，导致没法用 Gastby Cloud 提供的默认 SSL 证书。）</span>
之后准备一有空闲就打开电脑，毕竟 13 寸的电脑也轻。

年内最好能找到一个 Star 数大于 300 的，可以持续贡献的开源项目做起来。
另外就是能写出至少一个爆款文章，这个有点看运气了，持续产出吧。

有一次看到有人说写作的秘诀是假装在和一个人讲话，试试看。

---

过去和现在一些写东西的地方集合：

1. 上一个博客：<a name="1">https://github.com/Cygra/blog</a>
2. Github Issues：<a name="2">https://github.com/Cygra/Cygra_la_Artis</a>
3. https://github.com/Cygra/useful_git_commands
4. 👍掘金：https://juejin.cn/user/325111174168302/posts
5. 👍Medium：https://medium.com/@cygraw
6. SegmentFault：https://segmentfault.com/u/cygra

其中，1、2、3 中的一些内容，可以整理一下到这个站点上，一些没有同步到 4 的内容同步到 4，repo 可以归档了。4 支持 markdown、用户多，可以继续长期维护。5 的文本编辑有点难用，写英文也有点累，会看心情写点 git 和 vim 相关的小品文吧。6 各方面（登录、编辑、消息通知等）都很难用，准备抛弃了。所以总结下来，后续会持续产出的是**本站、掘金、Medium**
