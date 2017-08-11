---
layout:     post
title:      "重装RStudio，中文显示乱码"
subtitle:   "R语言学习笔记"
date:       2017-06-13
author:     "Xu Zhixun"
header-img: "img/post-bg-unix-linux.jpg"
tags:
    - 笔记
    - R语言
    - 数据
---

毕业论文终稿定稿后，迫不及待升级了系统并重置了电脑。重新安装完RStudio后发现原来的项目，现在打开后，中文注释统统乱码。

![中文乱码](/img/in-post/20170613/1.png)

#### 解决办法

1. 设置Rstudio文本默认编码为UTF-8；
2. 用File -> Reopen with encoding，重新打开项目。

#### 图示

![2](/img/in-post/20170613/2.png)

![3](/img/in-post/20170613/3.png)

选择File -> Reopen with encoding菜单，出现下面界面，选择UTF-8，即可。

![4](/img/in-post/20170613/4.png)

![5](/img/in-post/20170613/5.png)