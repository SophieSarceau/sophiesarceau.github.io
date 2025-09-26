---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->

I work at the intersection of AI and the life sciences, especially AI for Proteins and structure‑based drug discovery.
Below are my publications by area.
Earlier work in mobile computing is also included.

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

### AI for Science

#### AI for Protein

<div class="publications">

{% bibliography --query @*[keywords~=ai4protein] %}

</div>

#### AI for Drug Discovery

<div class="publications">

{% bibliography --query @*[keywords~=aidd] %}

</div>

#### Other

<div class="publications">

{% bibliography --query @*[keywords=ai4s] %}

</div>


### AI for Health

<div class="publications">

{% bibliography --query @*[keywords~=ai4health] %}

</div>

### Mobile Computing
I no longer work in this area, but here are some of my past publications.

<div class="publications">

{% bibliography --query @*[keywords~=mobilecomputing] %}

</div>
