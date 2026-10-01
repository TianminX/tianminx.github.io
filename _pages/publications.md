---
layout: page
permalink: /publications/
title: Publications
description: Journal articles and preprints.
nav: true
nav_order: 1
_styles: >
  .publication-note { color: var(--global-text-color-light); font-size: 0.9rem; }
  .publications h2.publication-category { margin-top: 2.5rem; margin-bottom: 0.65rem; padding-bottom: 0.5rem;
  border-bottom: 1px solid var(--global-divider-color); font-size: 1.45rem; }
  .publications h2.publication-category:first-child { margin-top: 0; }
---

<!-- _pages/publications.md -->

<p class="publication-note"><sup>*</sup> Equal contribution.</p>

<div class="publications">

<h2 class="publication-category">Preprints and Manuscripts Under Review</h2>
{% bibliography --group_by none --query @*[category=preprint]* %}

<h2 class="publication-category">Journal Articles</h2>
{% bibliography --group_by none --query @*[category=published]* %}

</div>
