---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: The History of Bronze Heads In The Old Summer Palace
layout: index
---
<img src = "{{exhibit.image-url}}" >
{% for exhibit in site.exhibits %}
<p>{{ exhibit.title }} by {{ exhibit.creator }}</p>

{% endfor %}