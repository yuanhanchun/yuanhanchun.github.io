---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
  - /cv-json/
  - /resume-json
---

**{{ site.author.name }}**

[{{ site.author.email }}](mailto:{{ site.author.email }}) · [Academic homepage]({{ '/' | relative_url }})

## Academic Appointment

**Lecturer**, College of Computer Science and Technology, Zhejiang Normal University

## Education

**Ph.D.**, Central South University

**Master's degree**, Central South University

## Research Interests

- Parameterized algorithms and approximation algorithms
- Graph modification problems
- Algorithms for block-structured integer programs

<h2>Journal Articles</h2>
{% for record in site.data.journal_articles %}
  {% include publication-list-item.html article=record %}
{% endfor %}

<h2>Conference Papers</h2>
{% for record in site.data.conference_papers %}
  {% include publication-list-item.html article=record %}
{% endfor %}
