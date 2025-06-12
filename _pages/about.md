---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am currently a Postdoctoral Researcher at the University of Twente. I earned my PhD from the same institution in 2025, under the supervision of [Prof. Dr. Ir. Raymond Veldhuis](https://scholar.google.com/citations?user=7BpMrY0AAAAJ&hl=nl), [Prof. Dr. Christoph Brune(https://scholar.google.com/citations?user=QkD3WhsAAAAJ&hl=en), and [Dr. Nicola Strisciuglio](https://scholar.google.it/citations?user=7cgpfGYAAAAJ&hl=it). My doctoral work focused on improving the robustness of vision models against common image corruptions such as noise and blur. I also contributed to a collaborative project with the BIOS Lab at the University of Twente, working on cell segmentation and classification.

My research interests lie in robustness, generalization, and efficient learning (from both model and data perspectives), as well as large language models.

# Publications 

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
