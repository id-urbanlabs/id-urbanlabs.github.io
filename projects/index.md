---
title: Projects
nav:
  order: 2
  tooltip: Ongoing projects and concepts
---

# {% include icon.html icon="fa-solid fa-city" %}Projects

Explore our portfolio of current initiatives and forward-looking ideas driving sustainable urban development. From ongoing projects shaping policy and practice to early-stage ideas still in formation, we aim to tackle Indonesia's urban challenges with data, collaboration, and innovation.

{% include project-tags.html %}

{% for project in site.data.projects %}
    {% include project-card.html project=project %}
{% endfor %}

## {% include icon.html icon="fa-solid fa-lightbulb" %}Other Emerging Topics
In addition to our main focus areas, we continue to explore a range of forward-looking themes that address evolving urban challenges. These topics reflect our ongoing curiosity and commitment to innovation in sustainable urban development:

- **Building Resilient Urban Food Systems**: Ensuring access and sustainability in metropolitan regions
- **Financial Strategies for Sustainable Metropolises**: Managing urban resources for inclusive development
- **Adaptive Governance in Metropolises**: Rethinking institutions to enhance resilience and responsiveness
- **Energy Transition in Tropical Cities**: Designing sustainable and context-sensitive urban energy systems
- **Feasibility of SNI ISO Standards**: Applying international frameworks for sustainable, smart, resilient Indonesian cities
- **Nonconventional Urban Mobility**: Innovating transport solutions in riverine, archipelagic, and mountainous regions
- **Gender in Urban Toponymy**: Exploring representation and equity in place-naming practices

These themes remain open for exploration and collaboration. If you're working on or interested in any of these areas, we'd love to [connect](/contact).
