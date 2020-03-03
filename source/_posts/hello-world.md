---
title: Hexo 搭建项目
date: 2020-03-02 14:39:53
---
# hexo + github 搭建
## 前言
随着互联网浪潮的翻腾，国内外涌现出越来越多优秀的社交网站让用户分享信息更加便捷。然后，如果你是一个不甘寂寞的程序猿（媛），是否也想要搭建一个属于自己的个人网站，如果你曾经或者现在正有这样的想法，请跟随这篇文章发挥你的Geek精神，让你快速拥有自己的博客网站，写文章记录生活，享受这种从0到1的过程。

## 搭建步骤
(在此处呢,我已经默认大家都已经安装过npm和node,直接进入主题吧)
* 安装hexo：
```
npm install hexo-cli -g
```
* 初始化博客目录：
```
hexo init wistbean.github.io (这里的wistbean换成你自己的英文名)
```
* 初始化完成后，我们就进入我们的目录：
```
cd wistbean.github.io
```
* 安装
```
npm install
```
* clean一下，然后生成静态页面
```
hexo clean
hexo g (g 就是generate ,生成的意思)
```
*把你的网站运行起来 (s 就是server ,在服务器运行的意思)
```
hexo s
```
* 打开你的浏览器，输入 localhost:4000 。 自此，你的个人网站就这么速度的搭建起来了!
<img src="/public/images/indexPage.png">

