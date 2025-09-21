---
permalink: /
title: "一段新旅程的起点"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
comments: true
---

<div class="lang-zh">
  
这是写在前面的话。

成立一个个人主页一直是我的一个小愿望，但我又总是一拖再拖。直到一个平平无奇的夏天的日子，天气晴朗，整个下午都无所事事，于是我就在偶然间完成了这个期待已久的事。过去，关于未来，我一直感到迷茫，迷茫于别人的人生与目光。但或许只有走下去，才知道属于你自己的生活是什么样。正如爱情需要体验，生活也是这样。那就让这个主页，作为一段新旅程的起点吧。

2025年8月

## 关于我自己

你好！我是高小叶，一个专注于自我内心的机器学习初学者，同时也是一个怀着作家梦想的孩子。虽然无论是学习，还是写作，都正如我的青春时光一般，才刚刚开始，但就算现在一无所有，我还是会勇敢地走下去。我相信只要怀揣着梦想和对生活的热爱，无论前路如何，都有一盏灯，温暖我的内心。

## 关于本站

这里是高小叶的个人主页，一个在互联网的海洋中，安放内心的小屋。屋子虽然不大，但温暖、舒服，就像一个随时可以停靠的港湾，在疲惫的时候，永远可以在这里慢慢地看一本书、喝一杯热茶。

我在小站上会发布一些科研日记（dairys），记录着我科研生活的点滴，或许只有一两句话，但都是我研究学习的脚印。我也会将一些完成好的项目（projects），发布在小站与github上，希望能对大家有帮助。无论你是好朋友还是陌生人，都欢迎在小站底部的评论区留言！我也希望我的生活能给你带来温暖。

## 最新日记
<ul class="archive__item-list">
{% assign dairys_sorted = site.dairys | sort: "date" | reverse %}
{% for diary in dairys_sorted limit: 3 %}
  <li><a href="{{ diary.url | relative_url }}">{{ diary.title }}</a>
      <small>({{ diary.date | date: "%Y-%m-%d" }})</small></li>
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

This is a note written at the beginning.

Creating a personal homepage has always been one of my small wishes, but I kept putting it off. Until one ordinary summer day, the weather was sunny, and the whole afternoon was idle, I accidentally completed this long-awaited thing. About the past and the future, I have always felt lost—lost in others’ lives and their gazes. But perhaps only by moving forward will you discover what your own life should be like. Just as love needs to be experienced, so does life. Let this homepage be the starting point of a new journey.

August 2025

## About Me

Hello! I am Gao XiaoYe, a beginner in machine learning who is focused on exploring my inner self, and also a child with a dream of becoming a writer.

Although both my studies and writing are just beginning, just like my youthful years, even if I have nothing now, I will still walk forward bravely. I believe that as long as I hold onto my dreams and my love for life, no matter how the road ahead may be, there will always be a light to warm my heart.

## About This Site

This is Gao Xiaoye’s personal homepage—a small hut in the vast ocean of the internet, a place to settle my heart. Although the hut is small, it is warm and cozy, like a harbor where one can always dock. When tired, you can always read a book here slowly or enjoy a cup of hot tea.

On this site, I will post some research diaries, recording bits and pieces of my academic life. Sometimes it may be only a sentence or two, but they are footprints of my research and study. I will also publish some completed projects here and on GitHub, hoping they will be helpful to others. Whether you are a good friend or a stranger, you are welcome to leave a message in the comment section at the bottom of the site! I also hope my life can bring warmth to you.

## Latest Diaries
<ul class="archive__item-list">
{% assign dairys_sorted = site.dairys | sort: "date" | reverse %}
{% for diary in dairys_sorted limit: 3 %}
  <li><a href="{{ diary.url | relative_url }}">{{ diary.title }}</a>
      <small>({{ diary.date | date: "%Y-%m-%d" }})</small></li>
{% endfor %}
</ul>

## Latest Projects
<ul class="archive__item-list">
{% for project in site.projects limit: 3 %}
<li><a href="{{ project.url | relative_url }}">{{ project.title }}</a></li>
{% endfor %}
</ul>

</div>

