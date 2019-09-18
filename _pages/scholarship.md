---
layout: page
permalink: /scholarship/
title: Scholarship
---
<!-- Recent Publications -->
### Recent Publications
{% for publication in site.data.publications limit:3 %}
<a href="https://luckyjimjd.github.io/assets/pdf/{{ publication.pdf }}" target="_blank">{{ publication.title }}</a>{% if publication.co-author %}, with {{ publication.co-author }}{% endif %}, {{ publication.volume }} {{ publication.container-title }} {{ publication.page }} ({{ publication.date }})
{% endfor %}



<!-- Work in Progress -->
# Work in Progress

{% for project in site.data.projects %}
<a href="{{ project.osf }}">{{ project.title }}</a>
{% endfor %}



