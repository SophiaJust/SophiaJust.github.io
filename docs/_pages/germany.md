---
layout: page
title: "GERMANY"
permalink: /germany/
---

{% for city in site.countries.germany %}
  <h2>{{ city.title }}</h2>
  <p>{{ city.content | markdownify }}</p>
{% endfor %}
