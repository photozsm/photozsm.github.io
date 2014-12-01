---
layout: page
title: Photoes in Tanzania
slug: tanzania
---

<div class="posts">

{% for post in site.categories.tanzania %}
 {% if post.url %}
  <div class="post">
       <span class="post-date">{{ post.date | date_to_string }}</span>
       {{ post.excerpt }}
  </div>
 {% endif %}
{% endfor %}
</div>


