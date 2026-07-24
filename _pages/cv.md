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
  <i>Thesis: *Studies on Flow Uniformization in Mixing Chambers using CFD - Analysis of the CLOUD experiment chamber at CERN* [PT](http://hdl.handle.net/10400.6/10068)</i><br>
  Merit Award — highest academic average in the MSc programme, 2018/2019

* **B.Sc. in Electromechanical Engineering**, University of Beira Interior, 2017

Experience
======
* **Mechanical Engineer**, CERN, Geneva, Switzerland  
  *Apr 2024–present*  
  <i>Design and simulation of high-power beam-intercepting systems for next-generation particle accelerators, with focus on CFD, multiphysics modelling, free-surface liquid-metal flows, heat transfer, thermal shocks, two-phase flow, and magnetohydrodynamics (MHD).</i>

* **Mechanical Engineer R&D Consultant**, University of Beira Interior, Covilhã, Portugal  
  *Jan 2024–Mar 2024*  
  <i>Developed machine-learning-enhanced digital twin workflows by coupling CFD/CHT simulations with Python-based data pipelines and neural network models for the prediction of thermal fields, hot spots, and flow behaviour in industrial systems.</i>

* **PhD Project Researcher**, Foundation for Science and Technology (FCT), University of Beira Interior, Covilhã, Portugal  
  *Sep 2019–Dec 2023*  
  <i>Developed custom multiphysics solvers in OpenFOAM for electrohydrodynamic, capillary, and multiphase flows, supported by large-scale HPC simulations, Python post-processing, and deep-learning-based surrogate modelling.</i>

* **Doctoral Research Internship**, West University of Timișoara, Faculty of Physics, Timișoara, Romania  
  *May 2023*  
  <i>Short-term doctoral mobility focused on Lattice Boltzmann Methods for fluid dynamics and GPU-based parallel computing for the acceleration of numerical simulations.</i>

* **Research Intern**, University of Beira Interior, Covilhã, Portugal  
  *Summer 2017*  
  <i>Computational modelling of three-dimensional flow structures in a disk pump/Tesla turbine using SolidWorks.</i>

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
* **Invited Talk**, [Global Symposium on Lead and Lead Alloy Cooled Nuclear Energy Science and Technology (GLANST 2024)](https://www.gen-4.org/resources/events/glanst-2024-global-symposium-lead-and-lead-alloy-cooled-nuclear-energy-science-and), ENEA Brasimone, Italy, 2024  
  *Development of Liquid Pb Technologies for Beam Intercepting Devices at CERN: A Case Study for Muon Collider Target and FCC-ee Beamstrahlung Absorber*  
  With M. Calviani, CERN
  
{% assign talks_sorted = site.talks | sort: "date" | reverse %}
<ul>
{% for post in talks_sorted %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

Skills
======
* **Simulation & Multiphysics:** CFD, CHT, multiphase flows, free-surface flows, turbulence modelling, heat transfer, thermo-mechanical analysis, FSI, MHD
* **Software & Tools:** OpenFOAM, ANSYS Fluent, ANSYS Mechanical, LS-DYNA, SolidWorks, SolidWorks Flow Simulation, Basilisk
* **Programming & Data:** Python, C++, MATLAB, SQL, PyTorch, Power BI
* **HPC & Workflows:** Linux, SLURM, parallel computing, automated post-processing, surrogate modelling
* **Certifications:** Certified SolidWorks Associate (CSWA), Lean Six Sigma Yellow Belt
* **Languages:** Portuguese, English, French

Service and Leadership
======
* **Secretary**, Rotaract Genève International, Geneva, Switzerland  
  *2026–2027*  
  <i>Member since 2026, contributing to the organization of service, networking, and community initiatives.</i>  
  [Website](https://geneve-international.rotaract.ch/en/)

* **Vice-President, Fiscal Council**, Happy Wish Junior Initiative, Covilhã, Portugal  
  *2022–2023*  
  <i>Supervised the financial management of the junior initiative and contributed to financial reporting activities.</i>  
  [LinkedIn](https://www.linkedin.com/company/happywish/posts/?feedView=all)

* **Finance Department Associate**, Happy Wish Junior Initiative, Covilhã, Portugal  
  *2021–2022*  
  <i>Supported financial management and administrative activities within the organization.</i>  
  [LinkedIn](https://www.linkedin.com/company/happywish/posts/?feedView=all)

* **Tutor**, STEAM Junior Academy, AJSTEAM UBI, Covilhã, Portugal  
  *March 2023*  
  <i>Supported educational activities promoting science, technology, engineering, arts, and mathematics.</i>

* **Conference Session Co-Chair**, ASME IMECE2021  
  *November 2021*  
  <i>Co-chaired a technical conference session on Aerodynamics & Novel Aerospace Propulsion Systems.</i>

* **Volunteer**, Refood Covilhã, Covilhã, Portugal  
  *2019–2024*  
  <i>Contributed to local food redistribution and community support activities.</i>
