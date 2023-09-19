---
title: "如何在 Andorid 设备（手机，pad，投影仪，电视等）上看电视直播"           # 文章标题
author: "grassto"              # 文章作者
date: 2023-09-18            # 文章编写日期
lastmod: 2023-09-18         # 文章修改日期
description : "电视、投影仪等设备，使用 TVBox 配置数据源用于看电视直播"    # 文章描述信息
slug: TVBox
# image: helena-hertz-wWZzXlDpMog-unsplash.jpg
categories:
    - play
keywords: [                # 文章关键词
    "影视资源",
    "投影仪",
    "TVBox",
]
tags: [                    # 文章所属标签
    "TV","Android",
]

#next: /tutorials/github-pages-blog      # 下一篇博客地址
#prev: /tutorials/automated-deployments  # 上一篇博客地址
---

推荐一个可以在 `Android` 设备上看 `CCTV` 的软件 `TVBox`，从此就可以不需要运行商的电视盒子就能够在只能电视、投影仪等设备上看电视直播了。

当然了，`TVBox` 不仅仅只能看电视直播，也会搜集网络上的影视资源，数据源好的情况下，当下热映的电影等都可以免费观看。


# 简明版

编译了一个自带数据源的版本，直接下载使用即可，[下载地址](https://own.grassto.top:8092/TVBox_os.apk)，服务器资源问题，下载可能有点慢，慢慢等等。

**注意：数据源是网络提供，当不可用时需要及时更换数据源，如果自己不会换数据源，可以联系我编译新的带源的应用再安装使用**。

好了，小白就不要再往下看了。

# 详细介绍

`TVBox` 的原理是网络搜集数据源，然后进行统一整合，我们能方便的观看影视节目，都需要感谢网上的大神无私地提供数据源。

数据源才是软件的核心。

## 下载 TVBox
两个版本，`takagen99` 和 `q215613905` 挑一个就行了。我平常比较喜欢使用 `takagen99` 的版本。

开源地址
- [takagen99/Box 源码](https://github.com/takagen99/Box)
- [q215613905/TVBoxOS 源码](https://github.com/q215613905/TVBoxOS)
- [releases下载](https://github.com/o0HalfLife0o/TVBoxOSC/releases)

## 配置数据源
以下数据源是当前能够使用的，若是之后不能使用，可以通知我进行更新。

> 打开软件 -> 设置 -> 配置地址 —> 地址填入点击确定

`q215613905` 版本只需要配置 数据源 即可，下面有地址。

`takagen99` 可以照着如下的去配置，嫌麻烦只配置第一个 数据源 即可。

- 数据源：[http://miaotvs.cn/meow](http://miaotvs.cn/meow)
- 直播源：[https://agit.ai/Yoursmile7/TVBox/raw/branch/master/live.txt](https://agit.ai/Yoursmile7/TVBox/raw/branch/master/live.txt)
- 直播 `EPG` 地址: [https://epg.112114.xyz/pp.xmlk](https://epg.112114.xyz/pp.xmlk)


## 注意事项
使用 `TVBox` 时，若是资源刷新不出来，可能是数据源失效了，需要去网上自行搜索替换新的数据源。

