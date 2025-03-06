---
layout: default
title: Home
---

<h2>Statistics Basics</h2>
<ul>
  {% for post in site.categories.basics %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<h2>Timely Topics</h2>
<ul>
  {% for post in site.categories["timely-topics"] %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


<h2>Thoughts and discussions</h2>
<ul>
  {% for post in site.categories.thoughts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
