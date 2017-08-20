---
layout: post-index
title: Tournaments
path: https://github.com/seanmerrow/heatgold/schedule
tag:
- tournament
category:
- tournament
---
{% for page in site.pages %}
  {% if page.categories contains 'tournament' %}
    <div class="item">
      <h3>{{page.title}}</h3>
      <p>{{page.description}}</p>  
    </div>
  {% endif %}
{% endfor %}
