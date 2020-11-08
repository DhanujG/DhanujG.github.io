---
layout: archive
title: "My Research Journey"
permalink: /research/
author_profile: true
---


Computational Ecology, Evolution and Biology Lab - University of Michigan
-----
* Machine Learning Dev. Student Research
  * Encoded Density Clustering ML Model, selected with DBCV analysis suite to identify coexistence among competing species contrary to existing principles of competitive exclusion. Model architecture and validation designed from recent ML research.
  * Created R package for Bio-Ecologists to easily structure trait data and perform Biological ML Clustering Analysis
  * Operate as an interdisciplinary reference within lab to explain and analyze machine learning and data analysis research.
  * Notable Technologies Used: Python, C++/C, R, MATLAB, Git



Michigan Medicine Computer Aided Diagnosis Laboratory - University of Michigan
-----
* Machine Learning & Computer Vision Student Research
  * Findings resulted as Primary Author in two Publications, was selected for Poster, Oral Presentation in SPIE Conference 2019
  * Performed Feature Extraction and Selection on Bladder CTU Scan Segmentations to extract key features in Bladder Cancer Lesion Staging (staging determines the avenue of treatment)
  * Implemented and trained a series of Back Propagated Neural Networks, Linear Discriminant Analysis, Support Vector Machines, and Random Forest Algorithms – validated through ROC analysis - resulting in a models' cancer staging accuracy (+80%)
  * Notable Technologies Used: C++, C, Python, Weka, MS Excel

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
