---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## In media:

- (In polish) "O unii rynków kapitałowych Unia Europejska dyskutuje już od dekady" as part of opinions column for Association of Polish Economists. [link](https://tep.org.pl/unia-rynkow-kapitalowych/)
- Quantocracy - [Monte Carlo option pricing – comparison of R and Julia languages](https://quantocracy.com/quantocracys-daily-wrap-for-12212020/)


## Research papers:

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
