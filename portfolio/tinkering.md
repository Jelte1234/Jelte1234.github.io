---
layout: default
title: "Tinkering"
menu_item: "Tinkering"
---


<div class="ui three column stackable doubling centered grid portfolio">
  {% for item in site.tinkering %}
  <a href="{{ item.url | relative_url }}" class="ui column portfolio-item">
    <img class="ui fluid rounded image" alt="{{ item.title }}" title="{{ item.name }}" src="{{ item.preview_image_url | relative_url }}"/>
  </a>
  {% endfor %}
</div>


