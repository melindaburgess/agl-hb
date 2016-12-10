---
layout: agl
title: Agile Government Handbook
---

{% assign ordered_sections = site.sections | sort: 'order' %}

<!-- Top in-page navigation links -->
{% include section_nav.html sections=ordered_sections %}

<!-- Section content -->
{% for section in ordered_sections %}
  {% include section.html section=section %}
{% endfor %}
