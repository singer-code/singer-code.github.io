---
layout: post
author: wangkaile
---
# 实验报告
## 一、网站目录结构
[网站目录结构](http://note.youdao.com/s/cyfUUGsY)
## 二、网站截图
[首页](http://note.youdao.com/s/6PUnYgB3)

[Blog列表页](http://note.youdao.com/s/Kppqcscz)

[posts-markdown练习](http://note.youdao.com/s/2p6FdrbS)

[posts-其他](http://note.youdao.com/s/3kWeLVyb)

[staff列表](http://note.youdao.com/s/5BeboaF6)

[staff-作者简介](http://note.youdao.com/s/LmnM6Kcu)

[staff-about](http://note.youdao.com/s/FxTy8ewV)

## 三、实验过程
### 下载
首先下载配置网站所需要的相关软件：ruby、visual code等。
### 按照教程依次做实验
按照jekyll的教程：step-by-step依次完成相关的实验
### nginx的安装与部署
按照教程安装nginx并将—site部署到nginx。但是并没有购买服务器和域名。
### push
将网站源代码push到github上，可以通过github给个人提供的io网站查看。
## 四、总结
这次实验真是让我感触良多。我遇到了很多问题，但是这些问题大多被解决了。
### 问题一：jekyll serve
当时在visual code上是没有办法运行jekyll serve这条语句的，没办法去请教老师，但是也没有解决。

因此我的解决办法简单粗暴。重新安装Ubuntu和visual code。这次反而可以运行了，很是神奇。但是第二次打开仍旧不可以，最后找到原因，权限太低，只要在前面加上“sudo”命令即可。

### 问题二：tree命令
我在ubuntu上使用tree命令无法显示，换了各种神奇的输入方式。

后来只能求助百度，结果是tree命令不是一个基础的命令，需要下载，成功解决。

### 问题三：push
关于如何将源代码push到github上，网上有很多教程。我根据其中一个教程成功将代码push到github上，但是实在过于麻烦。

于是发现最简单的方式是直接拖拽文件到github上即可。

### 问题三：markdown本地图片
关于如何将本地图片放在markdown里，其菜鸟教程里并没有写。

所以我通过查资料找到的解决办法是：下载有道云，把图片放在云盘里并且分享，将分享的链接作为图片的链接XD

### 心得
一个是学习了jekyll来做一个简单的静态网站，掌握了jekyll的各种用法。比如发表文章，同时带有作者的署名和实现文章与作者的对应。

另外一点是学会了visual code的基本操作方法。发现visual比较好用。

最后是进一步巩固了linux系统的使用与学习，发现linux系统相比于Windows更加的方便。当然这只是目前从安装软件的角度感觉到的，以后可能会有更多的惊喜。

当然，在本次实验中，我觉得在各种情况下都无法实现，但是通过努力解决问题并且取得成功的那一刻是非常有幸福感的。



