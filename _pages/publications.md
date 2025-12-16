---
title: Publications
permalink: /publications/
---
## Journal Articles

{% for publication in site.publications %}
- {{ publication.citation }}
{% endfor %}
