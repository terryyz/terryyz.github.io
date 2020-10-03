---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

1. COSMO: Conditional SEQ2SEQ-based Mixture Model for Zero-ShotCommonsense Question Answering  
    Farhad Moghimifar, Lizhen Qu, **Yue Zhuo**, Mahsa Baktashmotlagh and Gholamreza Haffari

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
