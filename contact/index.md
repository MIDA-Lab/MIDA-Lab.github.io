---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

{%
  include button.html
  type="email"
  text="mxian@uidaho.edu"
  link="mxian@uidaho.edu"
%}
{%
  include button.html
  type="phone"
  text="(208) 757-5425"
  link="+1-208-757-5425"
%}

{% include section.html %}

{% capture col1 %}
# Moscow campus
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2734.9540624984666!2d-117.01990438843507!3d46.72636757100221!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x54a027858d8eaab3%3A0x708f9a4585cbfc08!2s875%20Perimeter%20Dr%2C%20Moscow%2C%20ID%2083844!5e0!3m2!1sen!2sus!4v1731532198997!5m2!1sen!2sus" height="300px" width="100%" style="border:0;"  allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
{% endcapture %}

{% capture col2 %}
# Idaho Falls campus
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2893.2662971353743!2d-112.0538541!3d43.5176393!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x53545bf44ae6aa27%3A0xcc5940bc2734506f!2s1776%20Science%20Center%20Dr%2C%20Idaho%20Falls%2C%20ID%2083402!5e0!3m2!1sen!2sus!4v1730706543609!5m2!1sen!2sus" height="300px" width="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
