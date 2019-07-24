---
title: "Research"
layout: archive
permalink: /research/
author_profile: true
---
<div class="grid__wrapper">
  {% assign collection = 'research' %}
  {% assign posts = (site[collection]|sort: 'date') | reverse  %}
  {% for post in posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>



