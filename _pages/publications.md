---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Selected publications. The complete publication record is available on <u><a href="https://scholar.google.com/citations?user=SdNOWvEAAAAJ&hl=en">my Google Scholar profile</a>.</u>

**Preprints**

* [**Design and modeling of a liquid-lead dump concept for beamstrahlung radiation absorption in the CERN Future Circular Electron–Positron Collider**](https://doi.org/10.48550/arXiv.2601.18470)  
**Candido, S.**, Ximenes, R. F., Lechner, A., Frasca, A., Lerner, G., Marcone, A. P., et al. (2026). arXiv preprint, arXiv:2601.18470.  
  *Presents the design and multiphysics assessment of a liquid-lead system for absorbing high-power beamstrahlung radiation in the FCC-ee, combining particle-transport calculations, free-surface CFD, heat transfer and engineering integration.*  

**Peer-reviewed journal articles**  

* [**Numerical investigation of electrospray plume control using high-voltage ring conductors**](https://doi.org/10.1016/j.jaerosci.2026.106814)  
Benmoussa, A., **Candido, S.**, Pendar, M. R., & Páscoa, J. C. (2026). *Journal of Aerosol Science*, 106814.  
*Investigates the use of high-voltage ring electrodes to control the acceleration, focusing and transport of charged droplets in electrospray plumes through coupled electrostatic and multiphase-flow simulations.*


{% for post in site.publications reversed %}
  {% unless post.pubtype == "conference" %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}

**Conference proceedings**

* [**Conceptual Comparison of Liquid Lead Flow Configurations for a Muon Collider**](https://www.ipac26.org/prepress/doi/jacow-ipac2026-mop7137/index.html)  
(2026). *17th International Particle Accelerator Conference (IPAC'26)*, Deauville, France.

* [**Comparative conceptual designs of liquid lead absorbers for the FCC-ee beamstrahlung dump**](https://www.ipac26.org/prepress/doi/jacow-ipac2026-mop7139/index.html)  
(2026). *17th International Particle Accelerator Conference (IPAC'26)*, Deauville, France.

* [**Conceptual design and optimization of a liquid lead circuit as beamstrahlung absorber for the CERN's FCC**](https://doi.org/10.18429/JACoW-IPAC2025-THPB018)  
(2025). *16th International Particle Accelerator Conference (IPAC'25)*, Taipei, Taiwan.

* [**Magnetohydrodynamic effects in liquid lead target concept for Muon Colliders**](https://doi.org/10.18429/JACoW-IPAC2025-THPB017)  
(2025). *16th International Particle Accelerator Conference (IPAC'25)*, Taipei, Taiwan.

* [**A Three-Dimensional Numerical Investigation of Taylor Cone Jet Instabilities Using the VOF Method**](https://doi.org/10.1115/IMECE2023-112763)  
**Cândido, S.**, & Páscoa, J. C. (2023). *ASME International Mechanical Engineering Congress & Exposition (IMECE2023)*, New Orleans, USA.

* [**Improving Efficiency of Automotive Coating and Curing Processes Through Deep Learning Algorithms and High-Fidelity CFD Modeling**](https://doi.org/10.1115/IMECE2023-112373)  
**Cândido, S.**, Pendar, M., & Páscoa, J. C. (2023). *ASME International Mechanical Engineering Congress & Exposition (IMECE2023)*, New Orleans, USA.

{% for post in site.publications reversed %}
  {% if post.pubtype == "conference" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
