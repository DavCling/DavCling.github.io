---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my little corner of the web. I am an economist with research interests in economic history and applied microeconomics. I am Associate Professor of Economics and Department Chair at Case Western Reserve University.

My current research interests include automation, language shift, religious identity, social status, and innovation. 

Selected Publications
--------

{% for post in site.highlights reversed %}
  {% include archive-single.html %}
{% endfor %}