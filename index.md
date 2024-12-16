---
title: Welcome to my blog
layout: default
---

<h1>{{ site.title }}</h1>
<p>{{ site.description }}</p>

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
  </li>
{% endfor %}
</ul>

