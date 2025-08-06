---
layout: page
permalink: /publications
title: publications
description: Peer Reviewed Work.
nav: false
nav_order: 2
categories: [journal,conference,misc,thesis]
---

<!-- _pages/publications.md -->
<div class="publications" id="publications">
{% for category in categories %}
  {% assign display_name = category %}
  {% if category == misc %}
    {% assign display_name = "workshops, patents and arxiv" %}
  {% endif %}
  {% bibliography --group_by none --sort_by year,month --order descending --query @*[type={{category}}]* %}
{% endfor%}

</div>
