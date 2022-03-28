---
layout: page
permalink: /publications/
title: publications
description:
years: [2021, 2020]
nav: true
---

Or you can check out my publications on <a href="https://scholar.google.com/citations?user=RUPxn_MAAAAJ">Google Scholar</a>.

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
