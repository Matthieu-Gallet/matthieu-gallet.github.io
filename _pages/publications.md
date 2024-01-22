---
layout: page
permalink: /publications/
title: Publications
#description: publications by categories in reversed chronological order.
years: [2024,2023]
year_conf: [2023,2022]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->

### Journal articles
<div class="publications">
{%- for y in page.years %}
  <!-- <h2 class="year">{{y}}</h2> -->
<hr>
  {% bibliography -f papers -q @article[year={{y}}]* %}
{% endfor %}
</div>

<br>

### Conference proceedings 
<div class="publications">
<hr>
{%- for y in page.year_conf %}
  <!-- <h2 class="year">{{y}}</h2> -->
  {% bibliography -f papers -q @inproceedings[year={{y}}]* %}
{% endfor %}
</div>

<br>

### Datasets
<div class="publications">
<hr>
  {% bibliography -f papers -q @dataset* %}
</div>  