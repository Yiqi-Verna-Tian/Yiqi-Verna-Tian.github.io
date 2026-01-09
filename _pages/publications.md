---
layout: page
permalink: /publications/
title: Publications
description: A list of my publications and research papers.
nav: true
nav_order: 2
---

<div class="publications">

{% bibliography --group_by year --group_order descending %}

</div>

<style>
.publications h2 {
  font-weight: bold;
  text-align: left;
  margin-top: 2rem;
  margin-bottom: 1rem;
  font-size: 1.5em;
  color: #333;
}
.publications h2:first-child {
  margin-top: 0;
}
</style>
