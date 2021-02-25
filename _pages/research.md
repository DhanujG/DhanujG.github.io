---
layout: archive
title: "My Research Journey"
permalink: /research/
author_profile: true
---
I have found some of my most rewarding work through my reserach, where I was allowed to pursue projects that fully utilized knowledge from all three of my degrees. These wonderful opportunities have allowed me to be published multiple times as a primary author, present on a podium in a national conference, and implement groundbreaking analysis within a new discipline. Below I have information from both the labs I have worked in as well as the papers that I have directly wrote/ contributed to.

Computational Ecology, Evolution and Biology Lab - University of Michigan
-----
* **Machine Learning Dev. Student Research**
  * [Lab Website](https://sites.google.com/umich.edu/ostlinglab/people?authuser=0)
  * Published open-source R package titled weightedClustSuite [R, C++, Python] for Machine Learning Density Clustering  & Validation, used on weighted species abundance data enabling identification of species distribution clusters [Link](https://github.com/DhanujG/weightedClustSuite)
  * Encoded Density Clustering ML Model, selected with DBCV analysis suite to identify coexistence among competing species contrary to existing principles of competitive exclusion. Model architecture and validation designed from recent ML research.
  * Operate as an interdisciplinary reference within lab to explain and analyze machine learning and data analysis research.
  * Notable Technologies Used: Python, C++/C, R, MATLAB, Git
  *[My Code](https://github.com/DhanujG/weightedClustSuite)



Michigan Medicine Computer Aided Diagnosis Laboratory - University of Michigan
-----
* **Machine Learning & Computer Vision Student Research**
  * [Lab Website](https://cad-ai.med.umich.edu/people)
  * Findings resulted as Primary Author in two Publications, was selected for Poster, Oral Presentation in [SPIE Conference](https://spie.org/conferences-and-exhibitions?SSO=1) 2019
  * Performed Feature Extraction and Selection on Bladder CTU Scan Segmentations to extract key features in Bladder Cancer Lesion Staging (staging determines the avenue of treatment)
  * Implemented and trained a series of Back Propagated Neural Networks, Linear Discriminant Analysis, Support Vector Machines, and Random Forest Algorithms – validated through ROC analysis - resulting in a models' cancer staging accuracy (+80%)
  * Notable Technologies Used: C++, C, Python, Weka, MS Excel
  * [Work Samples](https://github.com/DhanujG/Bladder-Cancer-Classification-using-ML-and-Computer-Vision-Research)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
