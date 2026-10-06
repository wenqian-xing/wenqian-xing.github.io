---
title: "CV"
permalink: /cv/
---

{% assign cv_pdf = '/CV_Xing.pdf' | relative_url %}

<p class="cv-download"><a href="{{ cv_pdf }}">Download CV (PDF)</a></p>

<object class="cv-embed" data="{{ cv_pdf }}#view=FitH" type="application/pdf" aria-label="CV of {{ site.author.name }}">
  <p>Your browser cannot display the PDF here. <a href="{{ cv_pdf }}">Open the CV</a> instead.</p>
</object>
