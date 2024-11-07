---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include portrait.html lookup="Min Xian" %}
{% include portrait.html lookup="Terry Soule" %}
{% include portrait.html lookup="Alex Vakanski" %}
{% include portrait.html lookup="Boyu Zhang" %}

# Ph.D. Students

{% include list.html data="members" component="portrait" filter="role == 'phd' and !alumni" %}

# M.S. Students

{% include list.html data="members" component="portrait" filter="role == 'ms' and !alumni" %}

# Previous Students

{% include list.html data="members" component="portrait" filter="alumni" style="small" %}
