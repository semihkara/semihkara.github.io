---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---

See my [Google Scholar](https://scholar.google.com/citations?user=H_0BwCYAAAAJ&hl=en) for a comprehensive list.

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<!-- {% include bib_search.liquid %} -->

<div class="publications">

<!-- Journal Publications -->
<div class="publication-subheader">Journal Publications</div>
{% bibliography --file journal %}

<!-- Conference Publications -->
<div class="publication-subheader">Conference Publications</div>
{% bibliography --file conference %}

<!-- Preprints -->
<div class="publication-subheader">Preprints</div>
{% bibliography --file preprint %}

</div>
