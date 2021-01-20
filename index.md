---
layout: home
---

Welcome to my new webpage!

{% for animal in site.data.animal %}
- The {{ animal.name }} is a {{ animal.size }} animal.
{% endfor %}


![image](https://user-images.githubusercontent.com/77243910/105170656-28b01000-5b15-11eb-9985-5e53cb1f47b0.png)
