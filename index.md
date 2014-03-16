---
layout: page
title: Fotavo blog
tagline: (description)
---
{% include JB/setup %}

<div class="posts">
  {% for post in site.posts %}
    <div class="page-header">
      <a class="h3" href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date_to_string }}</span>
    </div>
  {% endfor %}
</div>

