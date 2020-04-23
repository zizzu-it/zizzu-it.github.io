---
layout: page
title:  "Kit di istruzioni per Enti"
permalink: "/il-kit/"
comments: true
---

<p>
    Il nostro obiettivo è di <strong>aiutare</strong> le Pubbliche Amministrazioni e le Associazioni di categoria.
    Nessun secondo fine, solo un aiuto in questo momento difficile.
    Per questo motivo desideriamo che essi abbiano il <strong>totale controllo</strong> sulle informazioni circolanti. La fonte di dati sarà sempre ufficiale, validata e monitorata da un soggetto istituzionale.
    Noi semplicemente rendiamo le informazioni più fruibile per l'utente finale.
</p>
<p>
    <h2>
        1. Creare una mappa
    </h2>
    In questo video vedrete come è possibile creare una propria mappa e posizionare gli esercizi commerciali nel posto giusto.
    <figure>
        <!-- <img src="https://cdn.dribbble.com/users/1073937/screenshots/5036567/waterfall.png" /> -->
    <iframe src="https://www.youtube.com/embed/9jO3kOueiv0?modestbranding=1&rel=0&showinfo=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
        <!-- <figcaption>Created by <a href="https://www.pasella.it" target="_blank_">Antonello Pasella</a></figcaption> -->
    </figure>
</p>
<p>
    <h2>
        2. Hai già una mappa?
    </h2>
    Se possedete già una mappa pubblica basata su Google My Maps, ArcGIS o UMap di OpenStreetMap potete 
    <a target="zizzu-mail" href="mailto:info@zizzu.it">potete contattarci direttamente</a>
     e provvederemo all'inclusione all'interno del servizio
</p>


{% if page.comments and site.show_comments == 1 %}
<aside class="comments" role="complementary">
    <div id="disqus_thread"></div>
    <script>
        var disqus_config = function () {
            this.page.url = '{{ page.url | prepend: site.baseurl | prepend: site.url }}';
            this.page.identifier = '{{ page.date | date: "%-m/%-d/%Y" }}';
        };
        (function() {
            var d = document, s = d.createElement('script');

            s.src = '//{{site.disqus}}.disqus.com/embed.js';

            s.setAttribute('data-timestamp', +new Date());
            (d.head || d.body).appendChild(s);
        })();
    </script>
</aside>
{% endif %}
