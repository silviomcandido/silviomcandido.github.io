---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Selected peer-reviewed journal publications. The complete publication record is available on <u><a href="https://scholar.google.pt/citations?hl=pt-PT&user=SdNOWvEAAAAJ">my Google Scholar profile</a>.</u>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
