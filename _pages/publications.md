---
layout: page
permalink: /publications/
title: Research
description: List of publications.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

## Working Papers

{% bibliography --query @*[category=pre-prints] %}

## Peer-Reviewed Publications

{% bibliography --query @*[category=peer-reviewed] %}

## Policy Papers

{% bibliography --query @*[category=policy-papers] %}
