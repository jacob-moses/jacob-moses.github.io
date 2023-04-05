---
layout: page
title: Academic CV
---

<h2>Education</h2>

{% for education in site.data.education %}
  <div class="row">
    <div class="col-md-4">
      <h4>{{ education.degree }}</h4>
      <p>{{ education.major }}</p>
    </div>
    <div class="col-md-4">
      <p class="text-muted">{{ education.school }}</p>
      <p>{{ education.graduation_date }}</p>
    </div>
  </div>
{% endfor %}

<h2>Employment</h2>

{% for employment in site.data.employment %}
  <div class="row">
    <div class="col-md-4">
      <h4>{{ employment.position }}</h4>
      <p class="text-muted">{{ employment.employer }}</p>
    </div>
    <div class="col-md-4">
      <p>{{ employment.dates }}</p>
    </div>
    <div class="col-md-4">
      <ul>
        {% for task in employment.tasks %}
          <li>{{ task }}</li>
        {% endfor %}
      </ul>
    </div>
  </div>
{% endfor %}

<h2>Publications</h2>

{% for publication in site.publications %}
  <div class="row">
    <div class="col-md-8">
      <h4>{{ publication.title }}</h4>
      <p>{{ publication.authors }}, <em>{{ publication.journal }}</em>, {{ publication.date }}</p>
      <p>{{ publication.description }}</p>
    </div>
  </div>
{% endfor %}

<h2>Presentations</h2>

{% for presentation in site.presentations %}
  <div class="row">
    <div class="col-md-8">
      <h4>{{ presentation.title }}</h4>
      <p>{{ presentation.date }}</p>
      <p>{{ presentation.description }}</p>
    </div>
  </div>
{% endfor %}
