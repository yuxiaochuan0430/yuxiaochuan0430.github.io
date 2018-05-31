---
title: Hexo  Manuals
date: 2018-05-31 16:00:16
tags:
---
一、创建和维护带图片的blog
1.安装插件hexo-asset-image.
``` bash
npm install hero-asset-image.
```

2.创建新blog
``` bash
hexo new "blog1"
```
得到_posts目录下
``` bash
![1](blog1/1.png)
```

3.在md中调用图片
![1](Hexo-Manuals/1.png)

4.hexo g 生成html
``` bash
<img src="/2018/5/31/blog1/1.png" alt="logo">
```