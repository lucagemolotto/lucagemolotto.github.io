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
* M.S. in Computer Science, University of Udine, 2024
  * Thesis: A General Purpose Runtime System for Choreographic Programming Languages for Robot Management
  * Supervisors: [Prof. Marco Comini](https://users.dimi.uniud.it/~marco.comini/) and [Prof. Marino Miculan](https://marino.miculan.org)
* B.S. in in Computer Science, University of Udine, 2021

Work experience
======
* February 2025 -- : Research Fellow under the Interreg IT-HR project "Brigantine"
  * University of Udine, [UNIUD Sailing Lab](https://lambda-iot.uniud.it/sailing_lab/website/)
  * Duties includes: Development of the data gathering and autonomous sailing layer of the catamaran and various engineering aspects.
  * Supervisor: Dr. Ivan Scagnetto

* March -- April 2024: Intern
  * Bruno Kessler Foundation, Formal Methods Unit
  * Developed a wrapper for NuRV, a tool for assumption-based Runtime Verification. The wrapper enabled the tool to support certain infinite-precision variables by booleanizing them. 
  * Supervisor: Dr. Stefano Tonetta

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
