---
layout: archive
title: "Selected Publications 1"
permalink: /publications1/
author_profile: true
---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=tnoge7wAAAAJ).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
