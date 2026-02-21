---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
_styles: |
  body .container.mt-5 {
    max-width: 100%;
    padding-left: 0;
    padding-right: 0;
  }

  body .post {
    max-width: 100%;
    margin: 0;
  }

  body .post-header {
    display: none;
  }

  .cv-embed {
    display: block;
    width: 100%;
    height: calc(100vh - 9rem);
    border: 0;
  }
---

<iframe
  class="cv-embed"
  src="{{ '/assets/pdf/cv.pdf' | relative_url }}"
  title="Curriculum Vitae"
></iframe>
