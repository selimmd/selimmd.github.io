---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my detail articles list on Google Scholar profile [link]("{{site.author.googlescholar}}"</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
