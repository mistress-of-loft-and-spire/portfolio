---
layout: default
title:  portfolio
---

{% for item in site.portfolio %}
<div class="entry {{ item }}">
  <h2>{{ item.title }}</h2>
  <p>{{ item.content }}</p>
</div>
{% endfor %}