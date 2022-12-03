---
layout: page
permalink: /Publications/
title: Publications (by topics)
description:
topics: ["otaa", "krr", "ml"]
otaa-years: [2022, 2020]
krr-years: [2022, 2021]
ml-years: [2022, 2021, 2020, 2019, 2018]
nav: true
---

View by topics
- <a href="#krr">Knowledge representation and reasoning</a>
- <a href="#otaa">Optimal transport algorithms and applications</a>
- <a href="#ml">Machine learning topic and applications</a>

<p> Or view in the <a href="/Publications-year/">chronological order</a> </p>

<div class="publications">

<h2 id='krr'>Knowledge representation and reasoning</h2>
{% for y in page.krr-years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f krr -q @*[year={{y}}]* %}
{% endfor %}


<h2 id='otaa'>Optimal transport algorithms and applications</h2>
{% for y in page.otaa-years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f otaa -q @*[year={{y}}]* %}
{% endfor %}


<h2 id='ml'>Machine learning topics and applications</h2>
{% for y in page.ml-years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f ml -q @*[year={{y}}]* %}
{% endfor %}

</div>
