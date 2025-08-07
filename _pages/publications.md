---
layout: page
permalink: /publications
title: publications
description: Peer Reviewed Work.
nav: false
nav_order: 2
categories: 
    - journal
    - conference
    - misc
    - thesis
---

<!-- _pages/publications.md -->
<div class="publications">
{% for category in page.categories %}
  {% assign display_name = category %}
  {% if category == "misc" %}
    {% assign display_name = "other venues" %}
  {% endif %}
  <h2 class="bibliography">{{ display_name }}</h2>
  {% bibliography --query @*[type={{ category }}] %}
{% endfor%}

</div>
