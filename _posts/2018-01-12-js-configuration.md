---
title: 关于NexT html5背景设置
date: 2018-01-12 14:16:48
author:     "myoungiron"
header-img: "img/home-bg-o.jpg"
catalog: true
tags: js
icon: "img/article_icon/technical_article_icon.png"
---
前几天你在查找东西的时候发现了几个不错的博客背景，我也来配置一下，这个背景是基于[particles.js](http://codepen.io/VincentGarreau/pen/pnlso)改过来的，比较简单

<!-- more -->
首先下载[particles.js](http://codepen.io/VincentGarreau/pen/pnlso)，简单的粒子效果只需要 app.js particles.js 这两个js文件就可以了。
把这两个js文件放到主题next目录下source\js\src,然后打开next目录下layout文件夹，这里就是next主题的一些配置，打开_layout.swig文件，将如下配置添加进去就可以了
``` bash
 <div id=particles-js style="position: fixed; width: 100%; height:100%"></div>
 <script type="text/javascript" src="/src/particles.js"></script>
 <script type="text/javascript" src="/src/app.js"></script>
```
script的引用路径根据自己的实际路径走

重启ok
