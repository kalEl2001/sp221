---
permalink: /ABOUT/
---

# About

This is the page for Samuel's journey on his system programming study.

<br>
# More Information

{% for ii in site.navbarlinks %}
  {% if ii.navbar == "GitHub" %}
    <a href="{{ ii.link | relative_url }}">{{ ii.navbar }}</a>
  {% endif %}
{% endfor %}
<br>

# Qapla!
