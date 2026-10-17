---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% assign cv_pdf = site.static_files | where: 'path', '/files/Yan_Luo_CV.pdf' | first %}
{% if cv_pdf %}
[**Download CV (PDF)**]({{ '/files/Yan_Luo_CV.pdf' | relative_url }}){: .btn .btn--primary }
{% endif %}

## Current Position

**Ph.D. Student in Astronomy**, Peking University<br>
Kavli Institute for Astronomy and Astrophysics (KIAA)<br>
Advisor: **Gregory J. Herczeg**<br>
2024–present

## Research Areas

Pre-main-sequence stellar evolution; young stellar populations; starspots and magnetic activity; lithium depletion; stellar rotation; Gaia spectroscopy and astrometry; empirical calibration of stellar masses and ages.

## Current Research

- Surface inhomogeneities and their impact on PMS stellar parameters and age determination
- The contribution of starspots to the observed lithium dispersion in young stars
- Gaia-based tests of coevality and evolutionary models using young wide binaries
- Dynamical-mass calibration of PMS evolutionary tracks
- Optical-to-infrared stellar spectroscopy with Gaia XP and SPHEREx

## Publications

See the [Publications]({{ '/publications/' | relative_url }}) page.
