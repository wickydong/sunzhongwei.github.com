---
layout: default
title: GitHub Pages 
---


# GitHub Pages


## Use markdown in GitHub Pages

直接创建后缀名字为 .md, 或者 .markdown 的文件即可。

但是首行需要加上

    ---
    title: This will be used as the title-tag of the page head
    ---

否则，Markdown 将不会被转换成  HTML.

所以，最好是 copy template.md 生存新文件。


## iPhone Safari 上查看中文显示乱码

Markdown 默认生成的 HTML charset 值不是 utf-8, 需要在模板文件中指定。
