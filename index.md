---
layout: default
title:  portfolio
---

{% for item in site.portfolio %}
<div class="entry-pic" style="background-image: {{ site.url }}/portfolio/img/{{ item.image }}">
</div>
<div class="entry">
  <h2>{{ item.title }}</h2>
  <p>{{ item.content }}</p>
</div>
{% endfor %}