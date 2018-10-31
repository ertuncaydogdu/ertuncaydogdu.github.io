---
layout: archive
title:
permalink: /resources/
author_profile: true
---

{% include base_path %}

## Statistics

* [**VanderPlas (SciPy, 2014)**](https://ertuncaydogdu.github.io/files/Frequentism.and.Bayesianism.pdf) provides a brief, semi-technical comparison of the essential features of the frequentist and Bayesian approaches to statistical inference, with several illustrative examples implemented in Python.

### Classical (Frequentist) Approach

{% for post in site.frequentism%}
  {% include archive-resource.html %}
{% endfor %}

### Bayesian Approach

{% for post in site.bayesianism%}
  {% include archive-resource.html %}
{% endfor %}

## Econometrics

Some background materials:

* XXX
* YYY

### Cross-section and Panel Data Methods 

{% for post in site.resources%}
  {% include archive-resource.html %}
{% endfor %}

### Bayesian Econometrics

{% for post in site.resources%}
  {% include archive-resource.html %}
{% endfor %}

### Financial Econometrics

{% for post in site.resources%}
  {% include archive-resource.html %}
{% endfor %}


