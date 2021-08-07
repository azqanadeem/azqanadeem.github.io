---
layout: page
permalink: /publications/
title: Research
description: 
years: [2018, 2019, 2020,2021]
categories: ['Workshop', 'Chapter', 'Poster']
nav: true
---

<div class="publications">

{% for cat in page.categories  %}
<h2 class="year">{{cat}}</h2>
{% for y in page.years reversed  %}
  {% bibliography -f papers -q @*[type={{cat}}]* %}
{% endfor %}

</div>
