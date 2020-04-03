---
layout: page
title: About
permalink: /about/
---

{% for team_member in site.team_members %}

  <h2>{{ team_member.name }}</h2>
  <img class="profilepic" src="{{ site.baseurl }}/images/{{ team_member.short }}.jpg">
  <p>{{ team_member.content | markdownify }}</p>

{% endfor %}
