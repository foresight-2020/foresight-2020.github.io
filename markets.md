---
layout: page
title: Markets
permalink: /markets/
---

<div class="column-header">Welcome to the Markets column of the site! Our goal here is to analyze markets, investment strategies, and businesses in a <span class="column-header-bold">data-driven way</span> &mdash; long on base rates and historical data and short on subjective opinion.
</div>
<div class="posts">
  {% for post in site.categories.Markets %}
    {% include postblurb.html %}

{% endfor %}

</div>
