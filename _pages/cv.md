---
layout: archive
title: "<i>Curriculum Vitae</i> <br> 🌱 <a href='/files/cv-SCandido.pdf'>PDF</a>"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<br>

Education
======
* Ph.D in Mechanical Engineering, University of Beira Interior, 2024
* M.S. in Electromechanical Engineering, University of Beira Interior, 2019
* B.S. in Electromechanical Engineering, University of Beira Interior, 2017

Experience
======
* 05/2023: Doctoral Research Internship, ERASMUS+, Romania
  * Universitatea de Vest din Timisoara, Facultatea de Fizica
  * <i>Short-term doctoral mobility scholarship, during which I developed proficiency in Lattice Boltzmann Methods for fluid dynamics. GPU computations to expedite complex calculations through parallel acceleration</i>

* Summer 2017: Research Intern, Covilhã, Portugal
  * University of Beira Interio
  * <i>Computational modelling of 3D flow structures on a disk pump (Tesla turbine) using SolidWorks </i>

Publications
======
{% assign publications_sorted = site.publications | sort: "date" | reverse %}
<ul>
{% for post in publications_sorted %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Communications
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Skills
======
* Mechanical Design with SolidWorks (CSWA)
* Lean Six Sigma (yellow belt)
* Computational Fluid Dynamics (CFD) (OpenFoam, Ansys Fluent)
* Python
* SQL (4h)
* PowerBI (31h)

Service and Leadership
======
* 2022-today: Vice-President Fiscal Council, Covilhã, Portugal
  * Happy Wish Junior Initiative (HW)
  * <i>Supervising the financial management of the HW Junior Initiative and performing a report
about financial activities.</i>

* 2021-today: Finance Department Associate, Covilhã, Portugal
  * Happy Wish Junior Initiative (HW)
  * <i>Support the financial management of the HW Junior Initiative.</i>
  
* Tutor at STEAM junior academy at AJSTEAM UBI, Covilhã, Portugal (March 2023)
* Conference Session Co-Chair at Conference IMECE2021 by ASME in the USA for Aerodynamics & Novel Aerospace Propulsion Systems topic (November 2021)
* Volunteer of Refood Covilhã, Covilhã, Portugal (2019-present)
