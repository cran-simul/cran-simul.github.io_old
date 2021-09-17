---
title: "SiMul research group @ CRAN - seminars"
layout: gridlay
excerpt: "SiMul research group @ CRAN: seminars"
sitemap: false
permalink: /seminars/
---

# Seminars

## Upcoming seminars
{% for seminar in site.data.seminarlist %}
{% if seminar.active == 1%}

  <b>{{ seminar.speaker }}</b> ({{seminar.institution}})<br/>
  {{seminar.date}}<br/>
   <em>{{ seminar.title }}</em><br />

<p>
    <button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#collapse-up-{{forloop.index}}" aria-expanded="false" aria-controls="collapse-u-{{forloop.index}}">
    Abstract
  </button>
</p>
<div class="collapse" id="collapse-up-{{forloop.index}}">
  <div class="card card-body">
{{seminar.abstract}}
  </div>
</div>
{% endif %}
{% endfor %}

## Past seminars

{% for seminar in site.data.seminarlist %}
{% if seminar.active == 0%}

  <b>{{ seminar.speaker }}</b> ({{seminar.institution}})<br/>
  {{seminar.date}}<br/>
   <em>{{ seminar.title }}</em><br />

<p>
    <button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#collapse-past-{{forloop.index}}" aria-expanded="false" aria-controls="collapse-past-{{forloop.index}}">
    Abstract
  </button>
</p>
<div class="collapse" id="collapse-past-{{forloop.index}}">
  <div class="card card-body">
{{seminar.abstract}}
  </div>
</div>
{% endif %}
{% endfor %}




