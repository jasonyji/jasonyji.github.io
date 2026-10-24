---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}
{% assign papers = site.research | sort: "order" %}

## Working Papers

<div class="research-cards">
{% for paper in papers %}{% if paper.section == "working" %}{% include research-card.html paper=paper %}{% endif %}{% endfor %}
</div>

## Work in Progress

<div class="research-cards">
{% for paper in papers %}{% if paper.section == "wip" %}{% include research-card.html paper=paper %}{% endif %}{% endfor %}
</div>
