---
layout: default
title: Casper L. Christensen
---

## Publications
{% assign pubs = site.publications | sort: "rank" %}
{% for p in pubs %}
  {% include pub.html pub=p %}
  {% unless forloop.last %}<hr class="pub-hr">{% endunless %}
{% endfor %}

<p><a href="/publications">See all publications →</a></p>
