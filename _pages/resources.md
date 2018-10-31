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

[**VanderPlas (SciPy, 2014)**](https://ertuncaydogdu.github.io/files/Frequentism.and.Bayesianism.pdf) provides a brief, semi-technical comparison of the essential features of the frequentist and Bayesian approaches to statistical inference, with several illustrative examples implemented in Python.

## Classical (Frequentist) Approach

{% for post in site.frequentism%}
  {% include archive-single-cv.html %}
{% endfor %}

## Bayesian Approach

{% for post in site.bayesianism%}
  {% include archive-single-cv.html %}
{% endfor %}
