---
layout: page
permalink: /committee/
title: Scientific Committee
nav: true
nav_order: 3
---
<div class="person_group_title">
    Meta Reviewers
</div>

<div>
{% for person in site.data.committee.meta_reviewer %}
    {% include committee_member.html %}
{% endfor %}
</div>

----------------------------------
<div class="person_group_title">
    Reviewers
</div>

<div>
{% for person in site.data.committee.reviewer %}
    {% include committee_member.html %}
{% endfor %}
</div>