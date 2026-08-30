---
layout: archive
title: "Publications"
description: "Peer-reviewed and working papers on systemic risk, financial contagion, business cycle transmission and computational economics."
permalink: /publications/
author_profile: true
---

My research is on systemic risk, financial contagion and business cycle transmission, with a
methodological interest in regime-switching models. I have presented most of this work at
[conferences and seminars](/talks/).

## Working papers

- **[Systemic Risk and Financial Connectedness: Empirical Evidence](https://m-dadej.github.io/files/connectedness.pdf)**, with Roberto Savona. [Replication code on GitHub](https://github.com/m-dadej/robust_fragile) and [slides from the Oxford FFM29 conference](https://m-dadej.github.io/files/empirical_oxford.pdf).
- **Risk Aversion Heterogeneity and Contagion in Endogenous Financial Networks**, with Andrea Modena. Draft coming soon.

## Opinion pieces

As part of the "TEP o gospodarce" opinion column of the Association of Polish Economists:

- <span lang="pl">"O unii rynków kapitałowych Unia Europejska dyskutuje już od dekady"</span> — [on the European capital markets union](https://tep.org.pl/unia-rynkow-kapitalowych/), 
- <span lang="pl">"Euroobligacje to szansa dla polityki gospodarczej UE"</span> — [on the eurobonds](https://tep.org.pl/euroobligacje-to-szansa-dla-polityki-gospodarczej-ue-tog-27-2025/)

## Published papers

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
