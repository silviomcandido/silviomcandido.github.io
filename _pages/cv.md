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
  Thesis: *Study of the Atomization of Electrohydrodynamic Jets: modelling, performance and applications* [LINK.PT](http://hdl.handle.net/10400.6/14426)  
  **Approved with Distinction**

* **M.Sc. in Electromechanical Engineering**, University of Beira Interior, 2019  
  Dissertation: *Studies on Flow Uniformization in Mixing Chambers using CFD - Analysis of the CLOUD experiment chamber at CERN* [LINK.PT](http://hdl.handle.net/10400.6/10068)<br>
  **Merit Award** — highest academic average in the MSc programme, 2018/2019

* **B.Sc. in Electromechanical Engineering**, University of Beira Interior, 2017

Experience
======
* **Mechanical Engineer / CERN Fellow**, CERN, Geneva, Switzerland  
  *Apr 2024–present*  
  Design and multiphysics analysis of high-power beam-intercepting systems for next-generation particle accelerators. Work includes thermal-fluid system development, free-surface liquid-metal flows, conjugate heat transfer, thermal shock, structural assessment, two-phase flow and magnetohydrodynamics. Responsible for translating simulation results into engineering concepts, operating requirements and design recommendations.

* **Mechanical Engineer R&D Consultant**, University of Beira Interior, Covilhã, Portugal  
  *Jan 2024–Mar 2024*  
  Developed computational workflows combining CFD, conjugate heat transfer, Python-based data processing and machine-learning models. The work focused on predicting thermal and flow fields, identifying hot spots and supporting the development of simulation-based industrial digital twins.

* **PhD Researcher — Computational Multiphysics**, Foundation for Science and Technology (FCT) & University of Beira Interior, Covilhã, Portugal  
  *Sep 2019–Dec 2023*  
  Developed custom OpenFOAM solvers for electrohydrodynamic, capillary and multiphase flows. Conducted large-scale HPC simulations, model verification and validation, Python-based data analysis, and reduced-order and deep-learning surrogate modelling.

* **Visiting Doctoral Researcher**, West University of Timișoara, Faculty of Physics, Timișoara, Romania  
  *May 2023*  
  <i>Short-term doctoral mobility focused on Lattice Boltzmann Methods for fluid dynamics and GPU-based parallel computing for the acceleration of numerical simulations.</i>

* **Research Intern**, University of Beira Interior, Covilhã, Portugal  
  *Summer 2017*  
  <i>Computational modelling of three-dimensional flow structures in a disk pump/Tesla turbine using SolidWorks.</i>

Publications
======
Selected key publications. The complete publication record is available on <u><a href="https://scholar.google.pt/citations?hl=pt-PT&user=SdNOWvEAAAAJ">my Google Scholar profile</a>.</u>

* [**Design and modeling of a liquid-lead dump concept for beamstrahlung radiation absorption in the CERN Future Circular Electron–Positron Collider**](https://doi.org/10.48550/arXiv.2601.18470)  
**Candido, S.**, Ximenes, R. F., Lechner, A., Frasca, A., Lerner, G., Marcone, A. P., et al. (2026). arXiv preprint, arXiv:2601.18470.  

* [**Numerical investigation of electrospray plume control using high-voltage ring conductors**](https://doi.org/10.1016/j.jaerosci.2026.106814)  
Benmoussa, A., **Candido, S.**, Pendar, M. R., & Páscoa, J. C. (2026). *Journal of Aerosol Science*, 106814.  

{% assign publications_sorted = site.publications | sort: "date" | reverse %}
<ul>
{% for post in publications_sorted %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Communications
======
* **Invited Talk**, [**Development of Liquid Pb Technologies for Beam Intercepting Devices at CERN: A Case Study for Muon Collider Target and FCC-ee Beamstrahlung Absorber**](https://www.gen-4.org/resources/events/glanst-2024-global-symposium-lead-and-lead-alloy-cooled-nuclear-energy-science-and)  
M. Calviani & S. Candido (CERN), *Global Symposium on Lead and Lead Alloy Cooled Nuclear Energy Science and Technology (GLANST 2024)*, ENEA Brasimone, Italy, 2024 
  
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
* **Programming & Data:** Python, C++, MATLAB, SQL, TensorFlow, Power BI
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
