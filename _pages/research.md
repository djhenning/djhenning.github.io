---
layout: page
permalink: /research/
title: Research
description:
years: [2023]
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->

#### Working Papers

<div class="publications">

    {% bibliography -f papers %}

</div>

<div class="unpublished">

{%- for y in page.years %}
  {% bibliography -f unpublished -q @*[year={{y}}]* %}
{% endfor %}

</div>
