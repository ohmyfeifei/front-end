# 浏览器

## 1. 概述

目前使用的主流浏览器有五个：Internet Explorer、Firefox、Safari、Chrome和Opera。虽然IE一直被喷，也被微软放弃了，但是IE的市场占有率还是蛮高的，特别是在中国。

[浏览器统计数据](http://gs.statcounter.com/#browser-CN-monthly-201507-201607)

## 2. 浏览器主要功能

浏览器的主要功能就是向服务器发出请求，在浏览器窗口中展示网络资源，最常见的网络资源当然就是HTML网页，其他还有pdf，图片等。

## 3. 浏览器的构成

![browser-layers.png](../../image/browser-layers.png)

一个浏览器的主要构成都有以下

1. 用户界面：除了浏览器窗口显示的页面外，其他显示的各个部分都属于用户界面。
2. 浏览器引擎：在用户界面和呈现引擎之间传送指令。
3. 渲染引擎：负责显示请求的内容，解析HTML和CSS。
4. 网络：用于网络调用，比如HTTP请求。其接口与平台无关，并为所有平台提供底层实现。
5. 用户界面后端：用于绘制基本的窗口小部件，例如组合框和窗口。
6. JavaScript解释器：用于解析和执行JavaScript代码
7. 数据存储：浏览器需要在硬盘上保存各种数据，例如Cookie。HTML5还定义了`网络数据库`（一个完整轻便的浏览器内数据库）。
 

## 4. 杂谈

按照正常来说，浏览器解析并显示HTML页面的方式是在HTML和CSS规范中指定的，这些规范由网络标准化组织[W3C](http://www.w3.org/)但是熟悉web开发的人都知道那段硝烟弥漫的浏览器之战的历史。这段历史虽然过去了，但还是留下了很多让前端开发人员头疼的兼容性问题。不过未来是光明的，浏览器的发展也越来越符合规范。就连微软也放弃IE，推出的全新的浏览器Edge基于依照这规范来实现，相当强大。

奇怪的是，浏览器的用户界面并没有任何正式的规范，却惊人地相似。它们的用户界面有很多彼此相同的元素，其中有：

* 用来输入URL的地址栏
* 前进和后退按钮
* 书签设置按钮
* 用于刷新和停止加载当前文档的刷新和停止按钮
* 用于返回主页的主页按钮

## 5. 来源

1. [浏览器的工作原理：新式网络浏览器幕后揭秘](http://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/#The_rendering_engines_threads)