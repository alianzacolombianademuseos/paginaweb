---
layout: page
title: "Paro Internacional de Museos"
permalink: "/museosenparo"
---

#MuseosEnParo
{% twitter https://twitter.com/hashtag/MuseosEnParo maxwidth=500 limit=5 %}

***

Adhesiones al :

<ul>
{% for adhesiones13m in site.data.adhesiones13m %}
    <li>
        <b>{{ adhesiones13m.institucion }}</b> <br>
        <i>{{ adhesiones13m.lugar }}</i>
    </li>
{% endfor %}
</ul>

>Adhesiones actualizadas el 2021-05-13 a las 11:00
