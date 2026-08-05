---
layout: page
permalink: /research/
title: Research
description:
nav: true
nav_order: 2
---
<style>
  html[data-theme="dark"] h2 {
    color: #ffffff !important;
  }
</style>
<!-- _pages/publications.md -->
<div class="publications">

<h2>Peer-Reviewed Publications</h2>
{% bibliography -f papers -q @*[keywords~=Peer-Reviewed Publications] %}

<h2>Working Papers</h2>
{% bibliography -f papers -q @*[keywords~=Working Papers] %}

<h2>In Preparation</h2>
{% bibliography -f papers -q @*[keywords~=In Preparation] %}

</div>
