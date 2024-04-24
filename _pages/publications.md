---
layout: archive
title: #"Publications"
permalink: /publications/
author_profile: true
---

**Publications**

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find full list of articles on my <a href="{{site.author.researchgate}}">ResearchGate profile</a> and <a href="{{site.author.googlescholar}}">Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
