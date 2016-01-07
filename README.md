Override
======

从mdwiki获得灵感制作的一个托管在github的博客，其原理是通过js来直接加载markdown文件动态解析成html，内容不用像Jekyll那样生成html而是保持markdown原文，这样就可以完美的使用markdown来写博客，可以直接在github完成博客的文字添加修改不用去Jekyll搞一堆参数了...


todo
=========
计划实现的内容

路径 
-------------
实现 普通博客的url

首页 http://djfly.github.io/ 自动加载 index.md 内容

首页翻页 http://djfly.github.io/page/2 加载/page/index.md 传入参数2

分类页 http://djfly.github.io/categories/ajax 加载/categories/index.md 传入参数ajax

分类页翻页 http://djfly.github.io/categories/ajax/2 加载/categories/index.md 传入参数ajax和2

标签页 http://djfly.github.io/tag/tools 加载/tag/index.md 传入参数tools

单独页 http://djfly.github.io/about/ 加载/about/index.md

内容页 http://djfly.github.io/2015/12/16/page-name 加载/2015/12/16/page-name.md

网站图标 favicon.ico
-------------
加载/favicon.ico

网站名称和title 
-------------
加载/site.md
```
Brand name
Home page title
```
页尾
-------------
加载/footer.md
```
&copy; Copyright Override 2016
```
菜单 
-------------
加载/navigation.md
例如：
```
[Home](home.md)
[About](about.md)
[Download](download.md)
```

语法高亮
-------------
...
评论加入disqus
-------------
...

