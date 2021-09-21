---
title: "SiMul research group @ CRAN - Publications"
layout: gridlay
excerpt: "SiMul research group @ CRAN -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

<!-- ## Group highlights

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p> -->


### Full list of publications from HAL

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
<div class="row">
<iframe width="100%" frameBorder="0" height="500px" src='https://haltools.archives-ouvertes.fr/Public/afficheRequetePubli.php?auteur_exp=David%2C+Brie%3B+El-Hadi%2C+Djermoune%3B+Sebastian%2C+Miron%3B+Konstantin%2C+Usevich%3B+Julien%2C+Flamant%3B&annee_publideb=2016&CB_auteur=oui&CB_titre=oui&CB_article=oui&langue=Anglais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&ordre_aff=TA&Fen=Aff&css=../css/VisuCondenseSsCadre.css' ></iframe>
</div>