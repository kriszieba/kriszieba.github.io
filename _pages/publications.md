---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Find my research publications on [Google Scholar](https://scholar.google.com/citations?user=ZPMM8YEAAAAJ&hl=no)

My PhD thesis is available [here](https://ntnuopen.ntnu.no/ntnu-xmlui/handle/11250/2423227)

