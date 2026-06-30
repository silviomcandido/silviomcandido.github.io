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
* **Ph.D. in Mechanical Engineering**, University of Beira Interior, 2024  
  Thesis: *Study of the Atomization of Electrohydrodynamic Jets: modelling, performance and applications* [PT](http://hdl.handle.net/10400.6/14426)

* **M.Sc. in Electromechanical Engineering**, University of Beira Interior, 2019  
  Thesis: *Studies on Flow Uniformization in Mixing Chambers using CFD - Analysis of the CLOUD experiment chamber at CERN* [PT](http://hdl.handle.net/10400.6/10068)

* **B.Sc. in Electromechanical Engineering**, University of Beira Interior, 2017

Experience
======
* **Apr 2024–present: Mechanical Engineer, Geneva, Switzerland**
  * CERN, European Organization for Nuclear Research
  * <i>Design and simulation of high-power beam-intercepting systems for next-generation particle accelerators, with focus on CFD, multiphysics modelling, free-surface liquid-metal flows, heat transfer, thermal shocks, two-phase flow, and magnetohydrodynamics (MHD).</i>

* **Jan 2024–Mar 2024: Mechanical Engineer R&D Consultant, Covilhã, Portugal**
  * University of Beira Interior
  * <i>Developed machine-learning-enhanced digital twin workflows by coupling CFD/CHT simulations with Python-based data pipelines and neural network models for the prediction of thermal fields, hot spots, and flow behaviour in industrial systems.</i>

* **2019–2023: PhD Project Researcher, Covilhã, Portugal**
  * Foundation for Science and Technology (FCT), University of Beira Interior
  * <i>Developed custom multiphysics solvers in OpenFOAM for electrohydrodynamic, capillary, and multiphase flows, supported by large-scale HPC simulations, Python post-processing, and deep-learning-based surrogate modelling.</i>

* **May 2023: Doctoral Research Internship, Timișoara, Romania**
  * West University of Timișoara, Faculty of Physics
  * <i>Short-term doctoral mobility focused on Lattice Boltzmann Methods for fluid dynamics and GPU-based parallel computing for the acceleration of numerical simulations.</i>

* **Summer 2017: Research Intern, Covilhã, Portugal**
  * University of Beira Interior
  * <i>Computational modelling of three-dimensional flow structures in a disk pump/Tesla turbine using SolidWorks.</i>

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
{% assign talks_sorted = site.talks | sort: "date" | reverse %}
<ul>
{% for post in talks_sorted %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>


Service and Leadership
======
* **2026–2027: Secretary, Geneva, Switzerland**
  * Rotaract Genève International — [Website](https://geneve-international.rotaract.ch/en/)
  * <i>Member since 2026, contributing to the organization of service, networking, and community initiatives.</i>

* **2022–2023: Vice-President, Fiscal Council, Covilhã, Portugal**
  * Happy Wish Junior Initiative — [LinkedIn](https://www.linkedin.com/company/happywish/posts/?feedView=all)
  * <i>Supervised the financial management of the junior initiative and contributed to financial reporting activities.</i>

* **2021–2022: Finance Department Associate, Covilhã, Portugal**
  * Happy Wish Junior Initiative — [LinkedIn](https://www.linkedin.com/company/happywish/posts/?feedView=all)
  * <i>Supported financial management and administrative activities within the organization.</i>

* **March 2023: Tutor, Covilhã, Portugal**
  * STEAM Junior Academy, AJSTEAM UBI
  * <i>Supported educational activities promoting science, technology, engineering, arts, and mathematics.</i>

* **November 2021: Conference Session Co-Chair**
  * ASME IMECE2021, Aerodynamics & Novel Aerospace Propulsion Systems
  * <i>Co-chaired a technical conference session in the area of aerodynamics and aerospace propulsion systems.</i>

* **2019–2024: Volunteer, Covilhã, Portugal**
  * Refood Covilhã
  * <i>Contributed to local food redistribution and community support activities.</i>


Skills
======
* **Simulation & Multiphysics:** CFD, CHT, multiphase flows, free-surface flows, turbulence modelling, heat transfer, thermo-mechanical analysis, FSI, MHD
* **Software & Tools:** OpenFOAM, ANSYS Fluent, ANSYS Mechanical, LS-DYNA, SolidWorks, SolidWorks Flow Simulation, Basilisk
* **Programming & Data:** Python, C++, MATLAB, SQL, PyTorch, Power BI
* **HPC & Workflows:** Linux, SLURM, parallel computing, automated post-processing, surrogate modelling
* **Certifications:** Certified SolidWorks Associate (CSWA), Lean Six Sigma Yellow Belt
* **Languages:** Portuguese, English, French
