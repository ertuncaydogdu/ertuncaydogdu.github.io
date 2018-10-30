---
layout: archive
title:
permalink: /resources/
author_profile: true
---

{% include base_path %}

Econometrics
===

{% for post in site.resources%}
  {% include archive-resource.html %}
{% endfor %}

Statistics
===

{% for post in site.publications%}
  {% include archive-resource.html %}
{% endfor %}


