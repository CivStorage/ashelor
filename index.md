---
layout: default
title: Ashelor Storage
---
{% for static in site.static_files %}
[{{ static.basename }}]({{ static.path | relative_url }})
{% endfor %}