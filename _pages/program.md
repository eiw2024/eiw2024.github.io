---
layout: page
permalink: /program/
title: Program
nav: true
nav_order: 1
---

<table>
  <thead>
    <tr>
      <th>Start Time</th>
      <th>End Time</th>
      <th>Program</th>
      <th>Speaker</th>
    </tr>
  </thead>
  <tbody>
    {% for event in site.data.program %}
      <tr>
        <td>{{ event.start }}</td>
        <td>{{ event.end }}</td>
        {% if event.title.speaker %}
          <td>{{ event.title.event }}</td>
          <td>{{ event.title.speaker }}</td>
        {% else %}
          <td colspan="3">{{ event.title }}</td>
        {% endif %}
      </tr>
    {% endfor %}
  </tbody>
</table>
