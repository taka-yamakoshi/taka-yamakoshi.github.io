---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

You can also find my articles on <a href="https://scholar.google.com/citations?user=WimaLM4AAAAJ&hl=en" target="_blank">my Google Scholar profile</a>.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
