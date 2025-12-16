---
title: Publications
permalink: /publications/
---

## Journal Articles
{% assign journal_articles = site.publications | where: "category", "journal-article" | sort: "date" | reverse %}
{% for publication in journal_articles %}
- {{ publication.citation }}
{% endfor %}

## Conference Participation
{% assign conference_articles = site.publications | where: "category", "conference" | sort: "date" | reverse %}
{% for publication in conference_articles %}
- {{ publication.citation }}
{% endfor %}

---

Find me on [Google Scholar](https://scholar.google.com/citations?user=YOUR_USER_ID_HERE)

