---
layout: publication
permalink: /publications/LiuAAMAS19/
author_profile: true
---
{% assign pub_key = "LiuAAMAS19" %}

{% include base_path %}
{% assign pub = null %}
{% for p in site.data.pubs %}
  {% if p.key == pub_key %}
    {% assign pub = p %}
    {% break %}
  {% endif %}
{% endfor %}
{% include pub-page.html %} 
     
         
