---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=HFj2KYkAAAAJ&hl=ca&oi=sra)

### Peer-reviewed publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

### Reports and non peer-reviewd publications

{% include base_path %}

{% for post in site._reports reversed %}
  {% include archive-single.html %}
{% endfor %}
