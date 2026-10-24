---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}
{% assign courses = site.courses | sort: "order" %}

## Teaching Assistantship

<div class="research-cards">
{% for course in courses %}{% if course.section == "ta" %}{% include course-card.html course=course %}{% endif %}{% endfor %}
</div>
