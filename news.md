---
layout: page
title: News
permalink: /news/
---

My recent news.

<ul class="listing">
{% for post in site.news %}
  {% capture y %}{{post.date | date:"%Y"}}{% endcapture %}
  {% if year != y %}
    {% assign year = y %}
    <li class="listing-seperator">{{ y }}</li>
  {% endif %}
  <li class="listing-item">
    <time datetime="{{ post.date | date:"%Y-%m-%d" }}">{{ post.date | date:"%Y-%m-%d" }}</time>
    {{ post.content | remove: '<p>' | remove: '</p>'}}
  </li>
{% endfor %}
</ul>

