---
layout:     post
title:      "如何基于github pages和jekyll搭建自己的个人博客"
date:       2021-04-09 14:31:00
author:     "xyc"
header-img: "img/post-bg-miui6.jpg"
tags:
    - github pages
    - jekyll
---

 
>学习的动力不应该是“焦虑”，而是“美好” 

## 前言

自己第一次利用github pages搭建blog，在感到新奇的同时也深感要学的东西还有许多。这个总结一是为了做一些记录，二是为了熟悉Markdown以及HTML语法。

[Github pages](https://pages.github.com/)使搭建个人静态博客变得更加容易，省去了租服务器的麻烦。事实上服务器是github免费提供的，我们只需要将网页的代码上传即可。我们可以使用官方推荐的静态()博客生成器[jekyll](https://jekyllrb.com/)（除了jekyll还有hexo等其他工具可以使用）创建网页模板，然后将其上传到github上就可以做出一个自己的github pages。

## 创建github仓库

* 创建一个新的github账号


* 新建一个仓库，并且命名为：“你的ID.github.io”
<img src="/img/in-post/2021.4/1.1.png" alt="图片无法加载时显示的文字">

## jekyll安装
jekyll是一种将纯文本转换成静态网站的工具(软件)，安装方法如下：

>~ $ gem install bundler jekyll

>~ $ jekyll new my-awesome-site

>~ $ cd my-awesome-site



## 后记

1. Markdown的语法可以在这里找到，有一些语法（比如表情）不一定适用全部平台）：[Markdown中文指南](https://www.markdown.xyz/basic-syntax/)

2. 中文版的jekyll文档：[jekyll中文版文档](https://jekyllcn.com/)

3. 在VS Code预览的时候，#与标题之间不加空格效果也是对的，但是上传后需要规范成 “#+空格+标题”。 Markdown有语法高度不统一的特点，如果对HTML很熟悉的话，还是建议直接写HTML。