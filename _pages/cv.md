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
* Ph.D in Recommender Systems, University of Cagliari, 2021 - Present
* M.S. in Computer Science, University of Cagliari, 2019 - 2021
* B.S. in Computer Science, University of Cagliari, 2016 - 2019

Work experience
======
* Maxtrino, Cagliari, IT
  * .Net Software Developer Intern, July 2019 – Sept. 2019
* Juvenile Court
  * Full Stack Web Developer Intern, March 2019 - July 2019

Projects
======
<ul>{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}</ul>

Skills
======
* Programming Proficiency
  * Python
  * C++
* Languages
  * English CAE
  * Italian Mothertongue

{% if site.publications %}
Publications
======
<ul>{% for post in site.publications %}
  {% include post %}
{% endfor %}</ul>
{% endif %}

{% if site.talks %}
Talks
======
  <ul>{% for post in site.talks %}
    {% include post %}
  {% endfor %}</ul>
{% endif %}

{% if site.teaching %}
Teaching
======
<ul>{% for post in site.teaching %}
  {% include post %}
{% endfor %}</ul>
{% endif %}

Service and leadership
======
* Student Volunteer: ACM Recsys21
