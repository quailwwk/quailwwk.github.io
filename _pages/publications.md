---
layout: archive
title: "Selected publications"
permalink: /publications/
author_profile: true
---
You can also find my other publications on <a href="https://scholar.google.com/citations?hl=en&user=JHI_UmQAAAAJ">my Google Scholar profile</a>.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


