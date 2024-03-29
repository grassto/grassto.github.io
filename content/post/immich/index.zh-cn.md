---
title: "手机相册照片同步"
author: "grassto"
date: 2023-09-19
lastmod: 2023-09-19
description : "翻看老照片，发现一些照片还是很有意义的，防止照片丢失，自己搭建了个同步归档服务器"
slug: photo
# image: helena-hertz-wWZzXlDpMog-unsplash.jpg
categories:
    - play
keywords: [
    "照片",
    "同步",
    "备份",
    "immich",
]
tags: [
    "照片","immich",
]

#next: /tutorials/github-pages-blog      # 下一篇博客地址
#prev: /tutorials/automated-deployments  # 上一篇博客地址
---

# 简介
不想再使用云服务商提供的备份服务了，想自己本地搭建一个？

那 immich 将是个好的选择，immich 是一个直接从 iPhone、Android 手机上备份照片与视频的开源解决方案，通过部署在自己的电脑、NAS、服务器中，使用 App 进行备份。界面酷似 Google Photos，支持多用户、照片和相册分享、好友上传、地理位置、机器学习识别事件等功能。


# 下载
- `Android` [GitHub release](https://github.com/immich-app/immich/releases/download/v1.77.0/app-release.apk)

- `iOS` 应用商店搜索 `immich` 安装即可。

图标长这样，别下错了
![图标](ico.png)


# 使用
1. 下载好应用，打开后第一步需要填写服务器地址 `https://own.grassto.top:8090`
![填写服务器地址](step1.png)

2. 点击进入下一个后，需要输入用户名密码
![用户名密码填写](step2.png)

3. 首次登录成功需要更改用户名密码
![更改密码](step3.png)

4. 使用修改后的密码登录，可以看到如下界面，如果图片比较多，需要等一会
![主页](step4.png)

5. 点击右上角的上传按钮，可以看到备份页面如下
![备份页](step5.png)

6. 首先需要选择需要备份的相册（正常情况下这个默认会选择 Recent 相册），不会操作可以跳过此步
![选择相册](step6.png)

7. 往下拉可以看到如下几个按钮，可以将“前台备份”，“后台服务” 都勾选上（若是都不勾选，每次都要手动点击最下方的 “开始备份”），然后点击最下方的 “开始备份”。

- 开启前台备份：程序打开时才进行备份。
- 开启后台服务：程序后台运行时也进行备份。
- 开始备份：需要手动点击一次，才会进行数据传输。

![开始备份](step7.png)


应用的功能还有很多，感兴趣的自行去探索。


# 开源库
[immich GitHub](https://github.com/immich-app/immich)
