---
layout: archive
title: "Coursework"
permalink: /coursework/
author_profile: true
---

## Doctoral Coursework

{% for group in site.data.coursework %}
<h3 class="coursework__field">{{ group.field }}</h3>
<div class="research-cards research-cards--grid">
{% for course in group.courses %}
  <div class="course-card">
    <span class="course-card__title">{{ course.name }}</span>
    <span class="research-card__authors">Instructor{% if course.instructors contains " and " %}s{% endif %}: {{ course.instructors }}</span>
    {% if course.audited or course.website %}
    <span class="course-card__extras">
      {% if course.audited %}<span class="course-card__tag">Audited</span>{% endif %}
      {% if course.website %}<a href="{{ course.website }}" target="_blank">Course Website &#8599;</a>{% endif %}
    </span>
    {% endif %}
  </div>
{% endfor %}
</div>
{% endfor %}
