---
layout: home
---

Welcome to my new webpage!

{% for animal in site.data.animals %}
- The {{ animal.name }} is a {{ animal.size }} animal.
{% endfor %}
