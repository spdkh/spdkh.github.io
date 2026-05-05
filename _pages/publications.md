---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

My current research is in **vision-based UAV navigation, geo-localization, and environmental monitoring**, and earlier in **physics-informed deep learning for computational imaging** (Structured Illumination Microscopy). Earlier publications covered electronics and FPGA design for the **Parsian / AUT-Parsian** RoboCup Small Size soccer-robot teams.

{% if author.googlescholar %}
A complete and continuously-updated list, including citation counts, is on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a></u>.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
