---
layout: page
permalink: /publications/
title: Articles
description: Publications by years in reversed chronological order
order: 2
years: [2022]
nav: true
---

## Published

<div class="publications">

{%- for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f published -q @*[year={{y}}]* %}
{% endfor %}

</div>

## Upcoming

### In the pipeline

{% bibliography --file in_production %}

### Under review

At the moment, 5 manuscripts are under review.

## Example: a mock contribution

This  page is  a reworking  of the  original t-SNE  article using  the
Computo template. It aims to help authors submitting to the journal by
using some advanced formatting features.

<div class="publications">

{% bibliography --file mock_papers %}

</div>

