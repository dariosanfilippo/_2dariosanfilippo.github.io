---
layout: page
permalink: /publications/
title: Publications
description:
a-years: [2022, 2021, 2019, 2018, 2013, 2012]
p-years: [2022, 2021, 2020, 2017, 2016, 2012]
t-years: [2020, 2013, 2011]
m-years: [2021, 2015, 2014, 2010, 2009]
nav: true
nav_order: 2
---

## Peer-Reviewed Journal Articles

<div class="publications">

{% for y in page.a-years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f articles -q @*[year={{y}}]* %}
{% endfor %}

</div>

___

<br>

## Peer-Reviewed Conference Papers

<div class="publications">

{% for y in page.p-years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers2 -q @*[year={{y}}]* %}
{% endfor %}

</div>

___

<br>

## Theses

<div class="publications">

{% for y in page.t-years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f theses -q @*[year={{y}}]* %}
{% endfor %}

</div>

___

<br>

## Music 

<div class="publications">

{% for y in page.m-years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f music -q @*[year={{y}}]* %}
{% endfor %}

</div>

