---
layout: page
title: About
permalink: /about/
---

<div class="about-header">Despite going to college a continent apart, Nihar and Bliss have remained great friends since they met nearly four years ago in India on their <a href="https://www.nsliforyouth.org/">NSLI-Y</a> scholarships. One of the things they enjoyed the most during their two summers living together was having impromptu discussions about international affairs and business. Recently, as these discussions have continued during quarantine via Zoom, they decided that they wanted to share their observations on this pivotal global crisis with the world. After they put their skills as programmers to the test coding a new website, they enlisted Bliss’s roommate Davis as a third contributor and Foresight is 20/20 was born. </div>
{% for team_member in site.team_members %}

  <h2>{{ team_member.name }}</h2>
  <img alt="{{ team_member.short }} profile picture" class="profilepic" src="{{ site.baseurl }}/images/{{ team_member.short }}.jpg">
  <p class="profile-blurb">{{ team_member.content | markdownify }}</p>

{% endfor %}
