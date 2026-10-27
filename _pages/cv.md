---
layout: single
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
cv_tab: cv
---

{% include cv-tabs.html %}

<iframe id="cv-frame" class="cv-frame" src="{{ '/files/cv-faruq-khadami.html' | relative_url }}" title="Curriculum Vitae Faruq Khadami" loading="lazy"></iframe>

<script>
  (function () {
    var f = document.getElementById('cv-frame');
    function fit() {
      try { f.style.height = (f.contentWindow.document.documentElement.scrollHeight + 24) + 'px'; } catch (e) {}
    }
    f.addEventListener('load', function () { fit(); setTimeout(fit, 600); });
    window.addEventListener('resize', fit);
  })();
</script>
