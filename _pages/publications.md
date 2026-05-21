---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
description: "Selected publications by Cong Liu in digital twins, XR, visual SLAM, 3D reconstruction, multi-view stereo, and human-AI interaction."
---

{% include base_path %}

<div class="publication-cta" markdown="1">
For richer project pages with PDFs, figures, and paper-specific resources, visit the publication hub:
[https://liu-publications-site.pages.dev/](https://liu-publications-site.pages.dev/)
</div>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
