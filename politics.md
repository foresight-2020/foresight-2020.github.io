---
layout: page
title: Politics
permalink: /politics/
---

<div class="column-header">
<a href="https://www.wsj.com/articles/the-coronavirus-pandemic-will-forever-alter-the-world-order-11585953005?shareToken=st72e8e1502ee847ddbe110335ee50772d">In a recent WSJ opinion piece</a>, Henry Kissinger wrote that "the coronavirus pandemic will forever alter the world order.” By now, with the world’s population potentially facing months of lockdown, that prediction seems like a foregone conclusion. Here, we’ll be exploring the multi-faceted and universal implications of the coronavirus crisis across the world to gain a sense of the inevitable shifts in global trends, drivers, and balance of power to come. </div>
<div class="posts">
  {% assign sortedPosts = site.categories.Politics | sort: 'date' %}
{% for post in sortedPosts reversed %}
    {% include postblurb.html %}

{% endfor %}

</div>
