---
title: Research
nav:
  order: 1
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

{% include section.html %}

## Highlighted

{% include citation.html lookup="mdpisi:1" style="rich" %}
{% include citation.html lookup="mdpisi:2" style="rich" %}

{% capture content %}
{% include citation.html lookup="hash:0dc460dd" style="rich" %}
{% include citation.html lookup="hash:bd895385" style="rich" %}
{% include citation.html lookup="hash:f4b51bc4" style="rich" %}
{% endcapture %}
{% include grid.html content=content %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" %}
