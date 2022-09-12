---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, my name is Valentin Gilbert, I'm a Ph.D student at [CEA List](http://www-list.cea.fr/) and [University Paris-Saclay](https://www.universite-paris-saclay.fr/). Before this specialization, I was a data engineer for two years, and I still have a strong interest in data science and building automated data pipelines for personal projects.

## Research topics
  * Quantum approximate Optimization Algorithm
  * Hybrid algorithms
  * Benchmark of Quantum computers
  * Quantum Error Correction

## Quantum posts

{% for post in site.quantumposts limit:3 %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

<!--
## Other posts

{% for post in site.otherposts limit:3 %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}
-->

## Aventures

{% for post in site.adventures limit:3 %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}