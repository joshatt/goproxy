---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
description: "文章的描述信息"
tags: [ "默认标签" ]
categories: [ "默认分类" ]
isCJKLanguage: true
weight: 0

# keywords: [ "keyword" ]
# linkTitle: ""

# 使用这两个参数将会重置permalink，默认使用文件名
#url: 
#slug: ""

# 设置文章的过期时间，如果是已过期的文章则不会发布，除非使用 --buildExpired 参数
# expiryDate: 2020-01-01

# 设置文章的发布时间，如果是未来的时间则不会发布，除非使用 --buildFuture 参数
# publishDate: 2020-01-01

# 别名将通过重定向实现
# aliases:
#   - 别名1
#   - /posts/my-original-url/
#   - /2010/01/01/another-url.html

# type 与 layout 参数将会改变 Hugo 寻找该文章模板的顺序
# type: review
# layout: reviewarticle
---

