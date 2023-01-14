---
layout: page
permalink: /publications/
title: Publications
#description: publications by categories in reversed chronological order.
years: [2022]
# year_pub: [2023,2020]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->

### Conference proceedings 
<div class="publications">
{%- for y in page.years %}
<!--  -->
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @inproceedings[year={{y}}]* %}
{% endfor %}
</div>

<!-- ### Journal articles
<div class="publications">
{%- for y in page.year_pub %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @article[year={{y}}]* %}
{% endfor %}
</div>
 -->
