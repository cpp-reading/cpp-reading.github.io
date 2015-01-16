---
layout: page
title: C++読書会in大阪のページ
tagline: C++11/14/17
---
{% include JB/setup %}

隔週月曜日 19:30～大阪で開催しているC++関係の本について意見を述べ合う、読書会のサイトです。

開催履歴

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
