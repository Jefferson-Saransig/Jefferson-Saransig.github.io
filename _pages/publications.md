---
title: Publications
permalink: /publications/
---
{% for publication in site.publications %}
{% if publication.category == "journal-article" %}
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
