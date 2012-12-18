---
layout: default
title: BackboneJS
---

# BackboneJS


## Router


### 前端 router 是什么

前端 Router 与后端 Router 的区别是，前端 Router 采用 #, 而后端采用 /, 例如

一个后端页面的地址是 /todos，那么在此单页 app 中，添加一个 todo 的地址就可以是

/todos/#add


### 什么时候应该使用前端 router

单页 app 中，当我们需要给用户发送一个特定功能页面的链接时，就需要用到前端 router。

例如，/#whois/dnspod.cn


### 什么时候不应该使用前端 router

当一个页面与当前单页 app 毫无关联的时候，就不应该使用前端 router。

例如，网站的 about me 页面，实际上与单页 app 毫无关系。这里就应该使用后端 router。




