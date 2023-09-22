---
layout: page
permalink: /speakers/
title: Speakers
nav: true
nav_order: 1
# description: This is a description of the page. You can modify it in 'pages/_cv.md'. You can also change or remove the top pdf download button.
---
**Corresponding Organizers**

<div class="img_group">
{% for person in site.data.speakers %}
    {% include committee_member_img.html %}
{% endfor %}
</div>
