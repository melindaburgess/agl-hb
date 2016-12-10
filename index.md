---
layout: agl
title: Agile Government Handbook
---

{% assign ordered_sections = site.sections | sort: 'order' %}

{% for section in ordered_sections %}

  {% include section.html section=section %}

{% endfor %}
