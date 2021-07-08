---
layout: page
title: About
description: 打码改变世界
keywords: Zhuang Ma, 马壮
comments: true
menu: 关于
permalink: /about/
---

<img src="C:\Users\黄新宇\Desktop\My_homepage\images\logo.png" alt="logo" style="zoom:50%;" />

***红颜零落岁将暮，寒光宛转时欲沉。***
***宁羞白发照清水，逢时壮飞思经纶。***
我是时欲沉，专注电力科学与人工智能交叉。
为美好生活充电，为美丽中国赋能。

## 联系

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
</ul>



