---
layout: archive
title: "Publications & talks"
permalink: /publications-talks/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single.html %}
  {% endfor %}</ul>
