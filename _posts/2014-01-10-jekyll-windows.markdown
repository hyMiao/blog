---
layout: post
title:  "Windows下配置jekyll本地环境"
author: Hy
date:   2014-01-10 08:50
categories: jekyll
---

忘记是什么时候看到的github+jekyll搭建静态博客的文章了...<br />
总之看完之后就觉得这个东西很好玩~于是想试着搞一下...<br />
无奈之前忙着复习考试没时间啊...趁着考完试了果断了搞了一发啊！<br />

不过这一段时间眼睛一直不舒服...没办法成天对着电脑...好影响效率...

下面开始说正经的事情！Jekyll在windows上的配置！<br />
（PS：其实在windows上装个linux虚拟机就可以不在这里开发了的...<br />

## 1、配置Ruby环境和DevKit环境

首先在[RubyInstaller](http://rubyinstaller.org/downloads/)下载合适的Ruby解释器和DevKit<br />
（有好多版本...可以去看一下具体的特性...要注意的是**所选择的Ruby和Devkit的版本一定要对应**）<br />
我的机器上安装的是`ruby2.0.0p247(x64)`和`DevKit-mingw64-64-4.7.2-20130224-1432-sfx`因为安装的比较早所以版本也比较...

## 2、安装python

看有的资料上面有写，但是因为我机器上本来已经配置过python，所以并不清楚它会不会造成影响
不过好像和后面用的高亮插件pygments有点关系...（毕竟这个是python来搞的
在[python](http://www.python.org/getit/)下载合适的版本并安装<br />

## 3、安装Jekyll
直接利用gem进行安装即可，执行：<br />
`gem install jekyll`

在cmd下执行`jekyll` 出现相关命令参数则证明安装成功

安装成功后试用一下jekyll吧：
(1)新建一个文件夹
(2)在cmd下进入该文件夹，执行命令`jekyll new <项目名称>`，例如：`jekyll a`建立新项目a
(3)进入项目文件夹执行指令`jekyll serve`启动服务器
(4)访问http:\\localhost:4000，出现Jekyll界面则证明配置成功

## 4、安装pygments
pygments是一个代码高亮插件，可以提供很便捷的


参考文章（1）：[Setup Jekyll on Windows][refer1]<br />
参考文章（2）：[windows下本地jekyll博客搭建手记][refer2]

[refer1]: http://yizeng.me/2013/05/10/setup-jekyll-on-windows/
[refer2]: http://blog.jsfor.com/skill/2013/09/07/jekyll-local-structures-notes/

