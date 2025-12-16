---
title: Publications
permalink: /publications/
---
{% assign sorted_publications = site.publications | sort: 'order' %}
{% for publication in sorted_publications %}
- {{ publication.citation }}
{% endif %}
{% endfor %}

## Conference Participation
{% for publication in site.publications %}
{% if publication.category == "conference" %}
- {{ publication.citation }}
{% endif %}
{% endfor %}

---


Find me on [Google Scholar](https://scholar.google.com/citations?user=YOUR_USER_ID_HERE)
