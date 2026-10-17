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

