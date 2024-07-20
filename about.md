---
permalink: /ABOUT/
---

# About

I am {{ site.author }}, {{ site.address }}
These are reciters sample from Quran.com. See also [quran.com/reciters/](https://quran.com/reciters/).

<br>
# More Information

<ul><li>
{% for ii in site.navbarlinks %}
  {% if ii.navbar == "GitHub Page" %}
    <a href="{{ ii.link | relative_url }}">{{ ii.navbar }}</a>
  {% endif %}
{% endfor %}
</li><li>
{% for ii in site.navbarlinks %}
  {% if ii.navbar == "GitHub" %}
    <a href="{{ ii.link | relative_url }}">{{ ii.navbar }}</a>
  {% endif %}
{% endfor %}
</li></ul><br>

# This is the Way!



