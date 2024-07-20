---
permalink: /ABOUT/
---

# About

I am {{ site.author }}, {{ site.address }}
This site is not related to quran.com. 
Its purpose is to make it easier to select reciters.


The project (quran.com) is open source and
is built as a collaboration between core team members and the Tarteel team.
For more details, see 
[quran.com/reciters](https://quran.com/reciters)
and [quran.com/about-us](https://quran.com/about-us).


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



