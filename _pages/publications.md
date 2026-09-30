---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 3
---

_styles: |
  .publication-title-legend {
    font-size: 0.55em;
    font-weight: normal;
    color: var(--global-theme-color);
  }

<!-- _pages/publications.md -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
