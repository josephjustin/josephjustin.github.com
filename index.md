---
layout: page
title: Hi!
tagline: I am a software consultant from Cochin, India doing full time freelance consulting since an year plus.  Welcome!
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



