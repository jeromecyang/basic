---
layout: page
title: 文章
permalink: /posts/
image: https://i.imgur.com/gYG4pwA.png
---

<div class="entries">
  {% assign posts = site.posts | where: "layout", "post" %}
  {% for post in posts %}
    {% include entry.html %}
  {% endfor %}
</div>