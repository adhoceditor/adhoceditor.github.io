---
layout: page
title: Ruby
---

<ul>
  {% for post in site.categories.ruby %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

