---
layout: page
permalink: /publications/
title: publications
description: Publications in reverse chronological order.
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

## Preprints

<div class="publications">

{% bibliography --query @*[journal~=arXiv] %}

</div>

## Journal and conference papers

<div class="publications">

{% bibliography --query @*[journal!~arXiv] %}

</div>
