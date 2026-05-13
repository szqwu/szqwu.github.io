---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently an MSR (MS in Robotics) student at [Carnegie Mellon University](https://www.cmu.edu/), advised by [Prof. Deva Ramanan](https://www.cs.cmu.edu/~deva/). 
Before that, I obtained my Bachelor of Science degree in Computer Science and Mathematics at [The Hong Kong University of Science and Technology](https://hkust.edu.hk/), where I worked with [Prof. Chi-Keung Tang](https://cse.hkust.edu.hk/~cktang/bio.html) and [Prof. Yu-Wing Tai](https://yuwingtai.github.io/).

My research interests lie in **computer vision**, **multimodality**, and **generative agents**, with a focus on bridging language models and embodied motion understanding.

I am actively looking for researcher / Ph.D. opportunities.

# Research

{% if site.publication_category %}
  {% for category in site.publication_category %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
---
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
