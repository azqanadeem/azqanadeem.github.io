---
layout: page
permalink: /misc/
title: Misc.
description: &ldquo; The earth has music for those who will listen &rdquo; &mdash; Reginald Holmes
nav: true
names: ['sc1', 'sc2', 'sc3', 'sc4', 'sc5', 'sc6', 'sc7', 'sc8', 'sc9']
---

<div class="news">
    <div class="table-responsive">
      <table class="table table-sm table-borderless">
        <tr>
          <td class="col-md-6">
            <img class="img-fluid z-depth-1 rounded" src="{{ '/portfolio/sc1.jpg' | prepend: '/assets/img/' | relative_url }}">
          </td>
		  <td class="col-md-6">
            <img class="img-fluid z-depth-1 rounded" src="{{ '/portfolio/sc2.jpg' | prepend: '/assets/img/' | relative_url }}">
          </td>
        </tr>
		
		<tr>
          <td class="col-md-6">
            <img class="img-fluid z-depth-1 rounded" src="{{ '/portfolio/sc3.jpg' | prepend: '/assets/img/' | relative_url }}">
          </td>
		  <td class="col-md-6">
            <img class="img-fluid z-depth-1 rounded" src="{{ '/portfolio/sc4.jpg' | prepend: '/assets/img/' | relative_url }}">
          </td>
        </tr>
		
		<tr>
          <td class="col-md-6">
            <img class="img-fluid z-depth-1 rounded" src="{{ '/portfolio/sc5.jpg' | prepend: '/assets/img/' | relative_url }}">
          </td>
		  <td class="col-md-6">
            <img class="img-fluid z-depth-1 rounded" src="{{ '/portfolio/sc6.jpg' | prepend: '/assets/img/' | relative_url }}">
          </td>
        </tr>
		
		<tr>
          <td class="col-md-6">
            <img class="img-fluid z-depth-1 rounded" src="{{ '/portfolio/sc7.jpg' | prepend: '/assets/img/' | relative_url }}">
          </td>
		  <td class="col-md-6">
            <img class="img-fluid z-depth-1 rounded" src="{{ '/portfolio/sc8.jpg' | prepend: '/assets/img/' | relative_url }}">
          </td>
        </tr>
		
		<tr>
          <td class="col-md-6">
            <img class="img-fluid z-depth-1 rounded" src="{{ '/portfolio/sc9.jpg' | prepend: '/assets/img/' | relative_url }}">
          </td>
		  <td class="col-md-6">
          </td>
        </tr>
      {% endfor %}
      </table>
    </div>
  {% else %}
    <p>No news so far...</p>
  {% endif %}
</div>

