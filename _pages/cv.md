---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science, University of Birmingham
* MSc in Computational Neuroscience and Cognitive Robotics, University of Birmingham
* B.S. in , Electrical and Electronic Engineering, Istanbul University



Collaborations
======
* Topological methods for measuring chromosomal instability (July 2026–present)
  * Institute for Data and AI, University of Birmingham
  * Supervised by Gianmarco Contino and Hamidreza Arjmandi
  * Copy number alteration (CNA)-based chromosomal instability (CIN) scores rely on arbitrary thresholds to decide when a segment's copy-number change counts as "unstable," so different studies using different cutoffs produce different, incomparable CIN scores and prognostic conclusions that shift with the threshold rather than the biology. This project addresses that by developing an applied topology (persistent homology) approach to CIN that derives instability from the multi-scale topological structure of the data itself, without requiring an arbitrary cutoff.
* Topological methods for risk stratification using heart-rate variability (ongoing)
  * With Grzegorz Graff and Beata Graff

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  