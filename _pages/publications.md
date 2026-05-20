---
layout: page
permalink: /publications/
title: activities
description: Journal articles, conference papers, presentations, and posters.
nav: true
nav_order: 2
---

<div class="publications">

<h2>Journals</h2>

{% bibliography --group_order descending --query @*[abbr=Journal]* %}

<h2>Conferences</h2>

{% bibliography --group_order descending --query @inproceedings* %}

<h2>arXiv</h2>

{% bibliography --group_order descending --query @*[abbr=arXiv]* %}

<h2>Posters</h2>

{% bibliography --group_order descending --query @*[abbr=Poster]* %}

<h2>Teaching</h2>

{% bibliography --group_order descending --query @*[abbr=Teaching]* %}

<h2>Presentations</h2>

{% bibliography --group_order descending --query @*[abbr=Talk]* %}

<h2>Podcasts</h2>

{% bibliography --group_order descending --query @*[abbr=Podcast]* %}

</div>
