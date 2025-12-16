---
title: Publications
permalink: /publications/
---
{% for publication in site.publications reversed %}
- {{ publication.citation }}
{% endfor %}

---

Find me on [Google Scholar](https://scholar.google.com/citations?user=YOUR_USER_ID_HERE)
