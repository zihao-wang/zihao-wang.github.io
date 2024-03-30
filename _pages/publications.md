---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 1
toc:
  beginning: true
---

Please check my
<a href="https://scholar.google.com/citations?user=T28rR00AAAAJ" target="_blank">
    <i class="ai ai-google-scholar"></i>
    Google Scholar
</a> or
<a href="https://www.semanticscholar.org/author/Zihao-Wang/1390878075" target="_blank">
    <i class="ai ai-semantic-scholar"></i>
    Semantic Scholar
</a>
page for the full publication list including preprints.

- [Machine Learning, Knowledge Representation, and Reasoning](#machine-learning-knowledge-representation-and-reasoning)
- [Other works in mathematical, medical, and physical sciences](#other-works-in-mathematical-medical-and-physical-sciences)
- [Preprints](#preprints)
- [Earlier works](#earlier-works)

The notations for equal contributions are omitted.

#### Machine Learning, Knowledge Representation, and Reasoning
<div class="publications">
{% bibliography -f {{ site.scholar.bibliography }} --query @*[visable=1]%}
</div>

#### Other works in mathematical, medical, and physical sciences
<div class="publications">
{% bibliography -f {{ site.scholar.bibliography }} --query @*[visable=2]%}
</div>

#### Preprints
<div class="publications">
{% bibliography -f {{ site.scholar.bibliography }} --query @*[visable=0]%}
</div>

#### Earlier works

<div class="publications">
{% bibliography -f {{ site.scholar.bibliography }} --query @*[visable=-1]%}
</div>