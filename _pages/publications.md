
---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<p>
My research spans computer architecture, hardware-software co-design,
high-performance computing, reliable FPGA/SoC systems, chiplet-based
architectures, and efficient AI acceleration.
My work has been published in peer-reviewed ACM and IEEE conferences
and journals, including ACM ICS, ACM GLSVLSI, and IEEE TCAD.
</p>

<p>
A complete and updated record of my research publications is also
available through my
<a href="https://scholar.google.com/citations?user=FnYbKDAAAAAJ">
Google Scholar profile</a>.
</p>

<p>
<strong>Research recognition:</strong>
Best Paper Award, IEEE Cloud Summit 2026,
for collaborative research on information-freshness-aware
scheduling in chiplet-based systems.
</p>

<hr>

{% include base_path %}

{% assign sorted_publications = site.publications | sort: "date" | reverse %}

{% for post in sorted_publications %}
  {% include archive-single.html %}
{% endfor %}
