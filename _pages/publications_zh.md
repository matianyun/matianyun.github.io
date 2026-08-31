---
layout: page
permalink: /zh/publications/
title: Publications
nav_title: 论文发表
lang: zh
lang_alt: /publications/
nav: true
nav_order: 2
---

<div class="publications selected-publications">

<div class="pub-filter-bar" role="group" aria-label="Filter publications by research area">
  <span class="filter-label">Filter</span>
  <button class="pub-filter-btn active" data-filter="all">All</button>
  <button class="pub-filter-btn" data-filter="arch-sys-for-ai">
    <span class="filter-dot"></span>
    Arch/Sys for AI
  </button>
  <button class="pub-filter-btn" data-filter="ai-for-chip">
    <span class="filter-dot"></span>
    AI for Chip
  </button>
  <button class="pub-filter-btn" data-filter="embodied-ai">
    <span class="filter-dot"></span>
    Embodied AI
  </button>
</div>

{% bibliography %}

</div>

<script src="{{ '/assets/js/pub-filter.js' | relative_url }}"></script>
