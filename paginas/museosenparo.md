---
layout: page
title: "Paro Internacional de Museos"
permalink: "/museosenparo"
---

![Museos en paro camapaña](https://pbs.twimg.com/media/E1H5vfTXIAQ6pZG?format=jpg&name=small)

Más información en redes sociales

[#museosenparo](https://twitter.com/hashtag/museosenparo)

[#MuseumsAreNotNeutral](https://twitter.com/hashtag/MuseumsAreNotNeutral)

[#SOSColombia](https://twitter.com/hashtag/SOSColombia)


***

## ¿quiénes se han adherido al Paro Internacional de Museos¿

<ul>
{% for adhesiones13m in site.data.adhesiones13m %}
    <li>
        <b>{{ adhesiones13m.institucion }}</b> <br>
        <i>{{ adhesiones13m.lugar }}</i>
    </li>
{% endfor %}
</ul>

>Adhesiones actualizadas el 2021-05-13 a las 11:00
