---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include team.html icon="/images/ancestors.svg" %}Team



{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}


{% include section.html %}


