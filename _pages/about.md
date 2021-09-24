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

If you peruse my research page you'll see I've published research on language, religious identity, social status, and innovation. I have used methods ranging from archival research to observational data to field experiments. 

Selected Publications
--------

{% for post in site.highlights reversed %}
  {% include archive-single.html %}
{% endfor %}