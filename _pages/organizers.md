---
layout: page
permalink: /organizers/
title: Organizers
nav: true
nav_order: 4
# description: This is a description of the page. You can modify it in 'pages/_cv.md'. You can also change or remove the top pdf download button.
---
**Corresponding Organizers**

<div class="img_group">
{% for person in site.data.organizers.main %}
    {% include committee_member_img.html %}
{% endfor %}
</div>

--------------

<div class="img_group">
{% for person in site.data.organizers.restss %}
    {% include committee_member_img.html %}
{% endfor %}
</div>