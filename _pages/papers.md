---
layout: page
permalink: /papers/
title: Accepted Submissions
nav: True
nav_order: 1
---

{% for entry in site.data.papers %}
  <div class="paper_entry">
    <h2>{{ entry.title }}</h2>
    <p>{{ entry.authors }}</p>
    <p>
      <a href="{{ entry.paper }}" style="font-weight: bold;">Paper</a> |
       <a href="{{ entry.poster }}" style="font-weight: bold;">Poster</a>
    </p>
    <hr>
  </div>
{% endfor %}
