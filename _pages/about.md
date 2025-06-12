---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am currently working as a Postdoc researcher at the University of Twente.  I received my doctoral degree from University of Twente in 2025, supervised by prof.dr.ir. Raymond Veldhuis, prof.dr. Christoph Brune, and dr. Nicola Strisciuglio. I worked on improving the robustness of vision models against common image degradations such as noise and blur and on cell segmentation and classification in a collaboration project with BIOS lab at the University of Twente.

My research interests include robustness, generalization, efficient learning (from both model and data perspectives), and large-language model.  


# Publications 

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
