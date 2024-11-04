---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include portrait.html lookup="Min Xian" %}
{% include portrait.html lookup="Alex Vakanski" %}
{% include portrait.html lookup="Boyu Zhang" %}

# Ph.D. Students

{% include list.html data="members" component="portrait" filter="role == 'phd' and !alumni" %}

# M.S. Students

{% include list.html data="members" component="portrait" filter="role == 'ms' and !alumni" %}

# Previous Students

{% include list.html data="members" component="portrait" filter="alumni" style="small" %}
