---
layout: page
title: "Paro Internacional de Museos"
permalink: "/museosenparo"
---

<a href="https://twitter.com/intent/tweet?button_hashtag=MuseosEnParo&ref_src=twsrc%5Etfw" class="twitter-hashtag-button" data-show-count="false">Tweet #MuseosEnParo</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
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
