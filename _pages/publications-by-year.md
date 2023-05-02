---
layout: page
permalink: /Publications-year/
title: Publications by Year
description:
years: [2023,2022,2021,2020,2019,2018,2017]
pyears: [2023,2022,2020]
nav: false
---

<div class="publications">

<h2>Peer Reviewed</h2>
{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

<h2>Preprints</h2>
{% for y in page.pyears %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f preprint -q @*[year={{y}}]* %}
{% endfor %}

</div>
