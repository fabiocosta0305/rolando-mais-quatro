---
layout: page
show_meta: false
subheadline: "Destino de Moreania"
title: "O Destino de Moreania"
teaser: "Minha Adaptação para Fate Core de Reinos de Moreania, o cenário oficial da DragonSlayer"
header:
    image_fullwidth: FundoBlog.png
permalink: "/fate-core/moreania/"
---
<ul>
{% for post in site.tags.Moreania %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
