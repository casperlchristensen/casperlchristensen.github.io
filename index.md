---
layout: default
title: Casper L. Christensen
---

# {{ site.title }}
Machine Learning Researcher from Denmark. My research interests are interpretability, robustness, and compositionality.

## Publications
{% assign pubs = site.publications | sort: "rank" | reverse | slice: 0, 6 %}
{% for p in pubs %}
  {% include pub.html pub=p %}
{% endfor %}

<p><a href="/publications">See all publications →</a></p>
