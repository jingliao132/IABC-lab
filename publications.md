---
layout: publication
title: Publications
description: Collections of research articles
author_profile: true
---

{% include site.baseurl %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
