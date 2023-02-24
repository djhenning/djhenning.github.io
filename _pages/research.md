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

<div class="publications">

    {% bibliography -f papers %}

</div>

#### Selected work in progress

<div class="unpublished">

{%- for y in page.years %}
  {% bibliography -f unpublished -q @*[year={{y}}]* %}
{% endfor %}

</div>
