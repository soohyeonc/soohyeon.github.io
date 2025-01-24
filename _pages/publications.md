---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=xWQGkacAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Preprints
---
1. I Can Find You in Seconds! Leveraging Large Language Models for Code Authorship Attribution \ 
Soohyeon Choi, Tan Yong Kiam, Mark Huasong Meng, Mohamed Ragab, Soumik Mondal, Khin Mi Mi Aung, and David Mohaisen \
[arXiv](https://arxiv.org/pdf/2501.08165) \

1. Attributing ChatGPT-Transformed Synthetic Code \
Soohyeon Choi, Ali Al Kinoon, Aziz Alghamdi,  Ahod Alguried and David Mohaisen \
Under review, @ IEEE International Conference on Distributed Computing Systems (ICDCS), 2025 \

