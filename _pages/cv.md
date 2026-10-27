---
layout: single
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<p><a class="btn btn--primary" href="{{ '/files/cv-faruq-khadami.html' | relative_url }}" target="_blank" rel="noopener">Buka CV di tab baru (cetak / simpan PDF)</a></p>

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
