---
layout: page
title: "GERMANY"
permalink: /germany/
---

Images of Marburg, Rehungen, Harsleben, Greifenhagen, Pfeiffhausen, and Bad Lauchstädt will be displayed here.

{% for country in site.countries %}
  <h2>{{ country.title }}</h2>
  <p>{{ country.content | markdownify }}</p>
{% endfor %}
