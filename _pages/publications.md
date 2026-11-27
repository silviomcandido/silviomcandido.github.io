---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}
<style>
  .pub-entry { display: flex; gap: 1.2em; align-items: flex-start; margin: 0 0 1.6em 0; font-size: 0.85em; }
  .pub-thumb { flex: 0 0 170px; }
  .pub-thumb img { width: 170px; height: 110px; object-fit: cover; border-radius: 4px; border: 1px solid #e5e5e5; }
  .pub-text { flex: 1; }
  .pub-title { font-weight: 600; }
  .pub-status { font-size: 0.75em; padding: 0.1em 0.5em; border-radius: 3px; background: #e8f3ec; color: #1e6b3a; }
  .pub-summary { margin-top: 0.35em; color: #555; }
  .pub-links { margin-top: 0.3em; font-size: 0.9em; }
  .pub-section { margin-top: 1.5em; }
  @media (max-width: 600px) { .pub-entry { flex-direction: column; } .pub-thumb, .pub-thumb img { width: 100%; height: auto; flex-basis: auto; } }
  .pub-entry.compact { margin-bottom: 0.9em; }
</style>

<p>Selected publications. The complete record is on <a href="https://scholar.google.com/citations?user=SdNOWvEAAAAJ&hl=en">Google Scholar</a>.</p>

{% assign pubs = site.publications | sort: "date" | reverse %}

<h2 class="pub-section">Journal articles</h2>
{% for post in pubs %}{% if post.pubtype == "journal" %}{% include pub-entry.html %}{% endif %}{% endfor %}

<h2 class="pub-section">Conference proceedings</h2>
{% for post in pubs %}{% if post.pubtype == "conference" %}{% include pub-entry.html %}{% endif %}{% endfor %}
