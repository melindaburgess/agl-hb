---
title:
order: 010
style: white
# NOTE: Enter in the list of sections, with the exact section title, below
#       Each section title entered will generate an 'anchor' link within the page
navigation_sections:
- About Agile
- Agile Manifesto
---

<div style="margin-top:-40px;">
<a href="http://www.agilegovleaders.org/" style="padding-right:30px;"><strong>AGL Home</strong></a> {% for section in page.navigation_sections %} <a href="#{{section|slugify}}" style="padding-right:30px;">{{section}}</a> {% endfor %}
</div>
