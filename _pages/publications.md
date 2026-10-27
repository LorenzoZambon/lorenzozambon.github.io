---
layout: page
permalink: /publications/
title: publications
description: Publications in reverse chronological order.
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

## Journal and conference papers

<div class="publications">

{% bibliography --query @*[journal!~arXiv] %}

</div>

## Preprints

<div class="publications">

{% bibliography --query @*[journal~=arXiv] %}

</div>
