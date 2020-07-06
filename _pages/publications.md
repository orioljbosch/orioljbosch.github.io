You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=HFj2KYkAAAAJ&hl=ca&oi=sra)


---
layout: archive
title: "Peer-reviewed publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


---
layout: archive
title: "Reports and non peer-reviewed publications"
permalink: /reports/
author_profile: true
---

{% for post in site.reports reversed %}
  {% include archive-single.html %}
{% endfor %}
