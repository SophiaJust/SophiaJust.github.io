---
layout: page
title: "GERMANY"
permalink: /germany/
---

{% for city in site.germany %}
  <h2>{{ germany.title }}</h2>
  <p>{{ germany.content | markdownify }}</p>
{% endfor %}
