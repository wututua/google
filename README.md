<h3 align="center">让我帮你Google一下</h3>

## 基本介绍

创意来自于「让我帮你百度一下」，这玩意出来好久了，同时，「让我帮你谷歌一下」也有，不过有各种不方便，要么就是年代久远，用的旧样式，要么就是境内访问有点难度。所以抽空改了一个出来。

感谢 [Sukka](https://github.com/SukkaW)提供网络环境判断方案。

基于这两个项目：[https://github.com/bangbang93/lmbtfy.cn](https://github.com/bangbang93/lmbtfy.cn) 以及 [https://github.com/mengkunsoft/lmbtfy](https://github.com/mengkunsoft/lmbtfy)

演示站点：[]()

## 食用注意

首先，环境需要 PHP，用于生成短链接用的；其次，要提到这个程序的一个优点，它可以判断使用者的网络能不能访问谷歌，如果不能，则调用反代站点访问。

但是这个反代站需要程序搭建者自己准备了，本程序自带的只能由我站调用。

编辑 lmgtfy.js ，把 google.wututu.cn 换成你自己的谷歌反代链接，实在没有就换成 www.google.com 吧。