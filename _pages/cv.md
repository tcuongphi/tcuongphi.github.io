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
* Ph.D in Mathematics, University Côte d'Azur, 2022 (supervised by Patricia Reynaud-Bouret and Eva Löcherbach)
* M.S. in Mathematics, University Côte d'Azur, 2018 (supervised by Patricia Reynaud-Bouret)
* B.S. in Mathematics, Hanoi National University of Education, 2016

Work experience
======
* [2023-2025]: Postdoc Researcher
  * Kyoto University, Japan

* 2019-2022: University teaching/research assistant
  * University Côte d'Azur, France

* [2017-2020]: Researcher
  * Institute of Mathematics Hanoi, Vietnam

  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
  

