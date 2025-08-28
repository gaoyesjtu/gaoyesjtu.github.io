---
permalink: /
title: "一段新旅程的起点"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="lang-zh">
  
这是写在前面的话。

成立一个个人主页一直是我的一个小愿望，但我又总是一拖再拖。直到一个平平无奇的夏天的日子，天气晴朗，整个下午都无所事事，于是我就在偶然间完成了这个期待已久的事。过去，关于未来，我一直感到迷茫，迷茫于别人的人生与目光。但或许只有走下去，才知道属于你自己的生活是什么样。就像爱情需要体验，生活也是这样。那就让这个主页，作为一段新旅程的起点吧。

2025年8月

## 关于我自己

你好！我是高小叶，一个专注于自我内心的机器学习初学者，同时也是一个怀着作家梦想的孩子。无论是学习，还是写作，都正如我的青春时光一般，才刚刚开始。可就算现在一无所有，可我还是会勇敢地走下去。我相信只要怀揣着梦想和对生活的热爱，无论前路如何，都有一盏灯，温暖我的内心。

---

## 最新日记
<ul class="archive__item-list">
{% for diary in site.dairys limit: 3 %}
<li><a href="{{ diary.url | relative_url }}">{{ diary.title }}</a> <small>({{ diary.date | date: "%Y-%m-%d" }})</small></li>
{% endfor %}
</ul>

## 最新项目
<ul class="archive__item-list">
{% for project in site.projects limit: 3 %}
<li><a href="{{ project.url | relative_url }}">{{ project.title }}</a></li>
{% endfor %}
</ul>

</div>

<div class="lang-en">
  Hello, I'm GaoYe, an AI researcher.
</div>
