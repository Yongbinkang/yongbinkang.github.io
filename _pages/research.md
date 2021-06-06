---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
# header:
#   og_image: "research/ecdf.png"
---

My primiary interest falls into the areas in analysing and discovering valuable/latent insights from real-life text data. Specifically, I am a data science researcher in Natural Language Processing (NLP), Machine Learning (ML), and Data Mining (DM). A summary of my research experitse and experiences is listed below:
  - 9+ years experience after PhD in research and development in data science, especially in the fields of NLP, ML and DM.
  - Significant experience in working and delivering industrial, multi-disciplinary research projects in data science: patent analytics, grey literature analytics, financial statement analytics, law sentence analytics, social-media data analytics, and expert finding. 
  - Special expertise in text mining, dynamic topic modeling, text summarisation, taxonomy learning, sentiment analysis, and deep learning.

## Latest research activities:

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}