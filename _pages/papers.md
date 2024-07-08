---
layout: page
permalink: /papers/
title: Accepted Papers
nav: True
nav_order: 1
---

{% for entry in site.data.papers %}
  <div class="paper_entry">
    <h2>{{ entry.title }}</h2>
    <p>{{ entry.authors }}</p>
    <p style="display: flex; justify-content: space-between;">
      <span>
        <a href="{{ entry.paper }}" style="font-weight: bold;">Paper</a> |
        <a href="{{ entry.poster }}" style="font-weight: bold;">Poster</a>
      </span>
      {% if entry.note %}
        <span class="sss" style="font-weight: bold; color: red; text-align: right;">
          {{ entry.note }}
        </span>
      {% endif %}
    </p>
    <hr>
  </div>
{% endfor %}
