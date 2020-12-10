---
layout: archive
title: "Publications"
permalink: /publications/
description: "Dr. Stefan Hofer, Postdoctoral Fellow at University of Oslo, Climate Scientist"
author_profile: true
---

This page contains a list of my publications, starting with my first author manuscripts. For more details, please visit my [Google Scholar profile](https://scholar.google.com/citations?user=HHacAS0AAAAJ&hl=en). I've tried to link PDFs of the final articles where the publishing license allows. Otherwise, please feel free to contact me if your institution doesn't provide with access to one of the articles below.

## Peer-reviewed Articles

## Comments, blog posts, and other non-peer-reviewed articles


## Reports



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
