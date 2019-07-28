---
title: "Pet Projects"
layout: archive
permalink: /fun/
author_profile: true
---
<div class="grid__wrapper">
  {% assign collection = 'fun' %}
  {% assign posts = site[collection]|sort: 'date' | reverse  %}
  {% for post in posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>



