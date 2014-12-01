---
layout: page
title: hongkong
slug: hongkong
---

<div class="posts">

{% for post in site.categories.hongkong %}
 {% if post.url %}
  <div class="post">
    <h2 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
       <span class="post-date">{{ post.date | date_to_string }}</span>
       {{ post.excerpt }}
  </div>
 {% endif %}
{% endfor %}
</div>


