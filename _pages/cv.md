---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: Nguyen_CV_Oct_2025.pdf # you can also use external links here
description: Please find my most updated CV here.
toc:
  sidebar: left
---
<!-- Embedded PDF preview -->
<iframe 
  src="{{ page.cv_pdf | relative_url }}" 
  width="100%" 
  height="1000px" 
  style="border:none;">
</iframe>

<!-- Download link -->
<p style="text-align:center; margin-top: 1em;">
  <a href="{{ page.cv_pdf | relative_url }}" target="_blank" class="btn btn--primary">
    Download CV (PDF)
  </a>
</p>