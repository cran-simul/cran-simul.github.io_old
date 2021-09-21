---
title: "SiMul research group @ CRAN - Team"
layout: gridlay
excerpt: "SiMul research group @ CRAN: Team members"
sitemap: false
permalink: /team/
---

# Group Members

 **We are  looking for new PhD students, Postdocs, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/jobs) **!**


Jump to [Faculty](#faculty), [Graduate students](#graduate-students), [alumni](#alumni), [visitors](#lab-visitors).

## Faculty
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} </i> <!--<br>email: <{{ member.email }}></i> -->
    <br/>
  {{member.keywords}}
  <br/>
  <ul class="list-inline">
  {% if member.email %}
  <li class="list-inline-item">
  <a href="mailto:firstname.lastname@univ-lorraine.fr"  title="email" class="no-mark-external">
    <span class="fa fa-envelope"></span>
    <!-- <span class="sr-only">{{ name }}</span> -->
  </a>
  </li>
  {% endif %}
  {% if member.website %}
  <li class="list-inline-item">
  <a href="{{member.website}}" title="personal website" class="no-mark-external">
    <span class="fa fa-globe"></span>
    <!-- <span class="sr-only">{{ name }}</span> -->
  </a>
  </li>
  {% endif %}
  {% if member.scholar %}
  <li class="list-inline-item">
  <a href="{{member.scholar}}" title="scholar" class="no-mark-external">
    <span class="ai ai-lg ai-google-scholar-square"></span>
    <!-- <span class="sr-only">{{ name }}</span> -->
  </a>
  </li>
  {% endif %}
  {% if member.researchgate %}
  <li class="list-inline-item">
  <a href="{{member.researchgate}}" title="rg" class="no-mark-external">
    <span class="ai ai-lg ai-researchgate-square"></span>
    <!-- <span class="sr-only">{{ name }}</span> -->
  </a>
  </li>
  {% endif %}
  </ul>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}




## Graduate students
{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} </i> <!--<br>email: <{{ member.email }}></i> -->
    <br/>
  {{member.keywords}}
  <br/>
  <ul class="list-inline">
  {% if member.email %}
  <li class="list-inline-item">
  <a href="mailto:firstname.lastname@univ-lorraine.fr"  title="email" class="no-mark-external">
    <span class="fa fa-envelope"></span>
    <!-- <span class="sr-only">{{ name }}</span> -->
  </a>
  </li>
  {% endif %}
  {% if member.website %}
  <li class="list-inline-item">
  <a href="{{member.website}}" title="personal website" class="no-mark-external">
    <span class="fa fa-globe"></span>
    <!-- <span class="sr-only">{{ name }}</span> -->
  </a>
  </li>
  {% endif %}
  {% if member.scholar %}
  <li class="list-inline-item">
  <a href="{{member.scholar}}" title="scholar" class="no-mark-external">
    <span class="ai ai-lg ai-google-scholar-square"></span>
    <!-- <span class="sr-only">{{ name }}</span> -->
  </a>
  </li>
  {% endif %}
  {% if member.researchgate %}
  <li class="list-inline-item">
  <a href="{{member.researchgate}}" title="rg" class="no-mark-external">
    <span class="ai ai-lg ai-researchgate-square"></span>
    <!-- <span class="sr-only">{{ name }}</span> -->
  </a>
  </li>
  {% endif %}
  </ul>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}




<!-- {% assign number_printed = 0 %}
{% for member in site.data.alumni_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }} <br> Role: {{ member.info }}</i>
  <ul style="overflow: hidden">

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %} -->

## Alumni
<div class="row">

<div class="col-sm-4 clearfix">
<h4>Visitors</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>PhD students</h4>
{% for member in site.data.alumni_phd %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Master students</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}
{% endfor %}
</div>

</div>


