---
layout: archive
title: "Publications"
description: "Peer-reviewed and working papers on systemic risk, financial contagion, business cycle transmission and computational economics."
permalink: /publications/
author_profile: true
---

## Opinion pieces

- (In polish) "O unii rynków kapitałowych Unia Europejska dyskutuje już od dekady" as part of opinions column for Association of Polish Economists. [link](https://tep.org.pl/unia-rynkow-kapitalowych/)

## Working papers:

- ["Systemic Risk and Financial Connectedness:
Empirical Evidence"](https://m-dadej.github.io/files/connectedness.pdf) with Roberto Savona. Check out the [code](https://github.com/m-dadej/robust_fragile) and [slides](https://m-dadej.github.io/files/empirical_oxford.pdf). 

- "Risk Aversion Heterogeneity and Contagion in
Endogenous Financial Networks" with Andrea Modena (Draft soon).

## Published papers:

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
