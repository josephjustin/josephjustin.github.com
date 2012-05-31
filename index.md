---
layout: page
title: Hi!
tagline: I am a Computer Programmer and FOSS consultant from Cochin, India.  Welcome to my site.
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



