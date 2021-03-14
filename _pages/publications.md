---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}


You can also find my articles on my [Scholar Google](https://scholar.google.com/citations?user=p1EfqNQAAAAJ&hl=en) and [ResearchGate](https://www.researchgate.net/profile/Martin-Belzunce) profiles.


## Peer-Reviewed Journal Publications

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## Conference Proceedings

{% for post in site.proceedings reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
