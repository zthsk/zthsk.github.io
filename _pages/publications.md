---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find my articles on <u><a href="https://scholar.google.com/citations?user=hEqZ5SIAAAAJ&hl=en">my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.type == 'conference' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}