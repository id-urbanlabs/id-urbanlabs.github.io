---
title: Projects
nav:
  order: 2
  tooltip: Ongoing projects and concepts
---

# {% include icon.html icon="fa-solid fa-city" %}Projects

Explore our portfolio of current initiatives and forward-looking ideas driving sustainable urban development. From ongoing projects shaping policy and practice to early-stage ideas still in formation, we aim to tackle Indonesia's urban challenges with data, collaboration, and innovation.
{% include section.html %}

{% include project-tags.html %}

{% for project in site.data.projects %}
    {% include project-card.html project=project %}
{% endfor %}
