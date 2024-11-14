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
{% include citation.html lookup="doi:10.1609/aaai.v38i5.28306" style="rich" %}
{% include citation.html lookup="doi:10.1007/978-3-031-43901-8_33" style="rich" %}
{% include citation.html lookup="doi:10.1007/978-3-031-16440-8_39" style="rich" %}
{% endcapture %}
{% include grid.html content=content %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" %}
