---
layout: page
title: "Paro Internacional de Museos"
permalink: "/museosenparo"
---

#MuseosEnParo

![Museos en paro camapaña](https://pbs.twimg.com/media/E1H5vfTXIAQ6pZG?format=jpg&name=small)

***

Adhesiones al Paro Internacional de Museos:

<ul>
{% for adhesiones13m in site.data.adhesiones13m %}
    <li>
        <b>{{ adhesiones13m.institucion }}</b> <br>
        <i>{{ adhesiones13m.lugar }}</i>
    </li>
{% endfor %}
</ul>

>Adhesiones actualizadas el 2021-05-13 a las 11:00
