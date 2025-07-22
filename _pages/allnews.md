---
title: "Paolucci Group - News"
layout: textlay
excerpt: "Paolucci Group at UVA."
sitemap: false
permalink: /news
---

# News

{% for article in site.data.news %}
<p><b>{{ article.date }}</b> <br> {{ article.headline}}</p>
{% endfor %}
