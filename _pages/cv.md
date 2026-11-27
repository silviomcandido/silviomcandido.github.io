---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a class="btn btn--primary" href="{{ base_path }}/files/cv-SCandido.pdf">Download CV (PDF)</a></p>

**Mechanical engineer (PhD)** developing high-power thermal-fluid and multiphysics systems from proof of concept to integration. Combines engineering design with CFD, heat-transfer and thermo-mechanical analysis, custom solver development and data-driven models.

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
* **Mechanical Engineer (CERN Fellow)**, CERN, Geneva, Switzerland  
  *Apr 2024–present* · High-power thermal-fluid, mechanical and systems engineering
  * **Delivered the baseline absorber for a 370 kW photon beam** at CERN's next collider (FCC-ee): conceived the CUSP liquid-lead concept, iterating free-surface configurations until the flowing lead absorbs ~95% of the deposited power, and took it from numerical proof of concept (multiphase CFD, conjugate heat transfer, structural analysis) to integration in the collider complex.
  * **Engineered the 300 kg/s liquid-lead circuit**: P&IDs, pipe sizing from flow and velocity limits, and hydraulic architecture (flow distribution, pumping, inventory, cover gas). Took part in the HAZOP as the system designer.
  * **Specified component requirements and interfaces**, including the electromagnetic pump for a supplier manufacturing study, and the system functional requirements for the FMEA, working with physics, radiation protection, materials, integration and external partners.
  * **Designed a graphite target for 2–4 MW pulsed beam loads**: helium-cooling optimisation, a titanium flow-guiding vessel, and verification of thermal stresses (ANSYS Mechanical) and thermal-shock stress waves (LS-DYNA).
  * **Proposed a compact liquid-lead jet target for 20 T magnetic fields**, using magnetohydrodynamic CFD to quantify jet deformation, electromagnetic damping and stability.

* **R&D Engineer — Computational Modelling**, C-MAST, University of Beira Interior, Portugal  
  *Jan 2024–Mar 2024*
  * Developed a 3D electrospray model (OpenFOAM/C++) predicting plume development and droplet deposition, with space-charge electric field and Coulomb and image forces coupled to the turbulent gas flow.
  * Optimised high-voltage ring electrodes for spray atomisation and plume control, validated against published experiments.

* **Doctoral Researcher**, University of Beira Interior / FCT, Portugal  
  *Sep 2019–Dec 2023*
  * Developed and validated a 3D two-phase electrohydrodynamic solver (OpenFOAM/C++), within 2% of benchmarks and experiments.
  * Developed an algorithm converting the broken-up liquid jet into individually tracked charged droplets, conserving mass, momentum and charge.
  * Developed surrogate models (modal decomposition and deep learning), reproducing deposition areas within ~1% from 10% of the simulations; published and open source.
  * Led the machine-learning development of an industrial digital twin for an automotive paint-curing oven.
  * Principal Investigator of two competitive national supercomputing projects (MPI, SLURM).

* **Visiting Doctoral Researcher**, Faculty of Physics, West University of Timișoara, Romania  
  *May 2023* · Lattice Boltzmann methods and GPU-parallel computing.

* **Research Intern**, University of Beira Interior, Portugal  
  *Summer 2017* · 3D flow structures in a disk pump / Tesla turbine.

Open-source code
======
* [interIsoFoamEHD](https://github.com/silviomcandido/interIsoFoamEHD) — electrohydrodynamic two-phase solver (OpenFOAM/C++)
* [electrostatic-spray-surrogate](https://github.com/silviomcandido/electrostatic-spray-surrogate) — surrogate models for electrostatic sprays (Python)

Publications
======
The complete publication record is available on <u><a href="https://scholar.google.com/citations?user=SdNOWvEAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% assign pubs = site.publications | sort: "date" | reverse %}
<style>.pub-entry { margin-bottom: 0.9em; } .pub-status { font-size: 0.75em; padding: 0.1em 0.5em; border-radius: 3px; background: #e8f3ec; color: #1e6b3a; } .pub-title { font-weight: 600; } .pub-links { display: none; }</style>

**Journal articles**

<div>{% for post in pubs %}{% if post.pubtype == "journal" %}{% include pub-entry.html compact=true %}{% endif %}{% endfor %}</div>

**Conference proceedings**

<div>{% for post in pubs %}{% if post.pubtype == "conference" %}{% include pub-entry.html compact=true %}{% endif %}{% endfor %}</div>

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
* **Design & systems engineering:** concept design and trade-offs, requirements and interface definition, hydraulic loop sizing, P&IDs, HAZOP and FMEA input, technical specifications, CAD
* **Thermal-fluid & structural analysis:** CFD, heat transfer, multiphase and liquid-metal flow, MHD, FEA, thermal stresses, explicit dynamics (shock)
* **Engineering software:** ANSYS Fluent and Mechanical, LS-DYNA, OpenFOAM, Basilisk, SolidWorks, CATIA
* **Programming & HPC:** Python, C++, MATLAB, machine learning (PyTorch, TensorFlow), Linux, MPI, SLURM
* **Certifications & courses:** Certified SolidWorks Associate (CSWA), Lean Six Sigma Yellow Belt; CADFEM (ANSYS & Python), VKI (Machine Learning for CFD)
* **Languages:** Portuguese (native), English (fluent, C1), French (A2)

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
