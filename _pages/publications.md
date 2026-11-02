
---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<p>
My research covers computer architecture, hardware-software co-design,
high-performance computing, FPGA/SoC systems, chiplet-based architectures,
and efficient AI acceleration.
</p>

<p>
My research has been published in peer-reviewed ACM and IEEE
conferences and journals, including ACM ICS, ACM GLSVLSI,
and IEEE TCAD.
</p>

<p>
For a complete publication list, please visit my
<a href="https://scholar.google.com/citations?user=FnYbKDAAAAAJ">
Google Scholar profile</a>.
</p>

<p>
<strong>Research Recognition:</strong>
Best Paper Award, IEEE Cloud Summit 2026,
for collaborative research on chiplet-based scheduling.
</p>

<hr>

{% include base_path %}

{% assign sorted_publications = site.publications | sort: "date" | reverse %}

{% for post in sorted_publications %}
  {% include archive-single.html %}
{% endfor %}
