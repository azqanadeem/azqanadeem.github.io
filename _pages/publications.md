---
layout: page
permalink: /research/
title: Research
description: See updated list on Google Scholar.
years: [2018, 2019, 2020,2021]
categories: ['Conferences and Symposia', 'Workshops', 'Chapters', 'Posters']
nav: true
---

<div class="publications">

<h2>Publications</h2>
{% for cat in page.categories  %}
	<h4>{{cat}}</h4>
	{% for y in page.years reversed  %}
		{%- capture citecount -%}
		{% bibliography_count -f papers -q @*[kind={{cat}} && year={{y}}]* %}
		{%- endcapture -%}

		{% if {{citecount}} != "0"  %}
			<h2 class="year">{{y}}</h2>
			{% bibliography -f papers -q @*[kind={{cat}} && year={{y}}]* %}
		{% endif %}
	{% endfor %}
{% endfor %}

</div>
