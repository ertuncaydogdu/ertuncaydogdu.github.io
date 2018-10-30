---
layout: archive
title:
permalink: /resources/
author_profile: true
---

{% include base_path %}

# Econometrics


{% for post in site.resources%}
  {% include archive-resource.html %}
{% endfor %}

# Statistics

A brief, semi-technical comparison of the es- sential features of the frequentist and Bayesian approaches to statistical infer- ence, with several illustrative examples implemented in Python. (avaialble at [**here**](https://ertuncaydogdu.github.io/files/Frequentism.and.Bayesianism.pdf).

## Classical (Frequentist) Approach

{% for post in site.publications%}
  {% include archive-resource.html %}
{% endfor %}

## Bayesian Approach

{% for post in site.publications%}
  {% include archive-resource.html %}
{% endfor %}
