---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## In media:
======

- (In polish) "O unii rynków kapitałowych Unia Europejska dyskutuje już od dekady" W ramach kolumny TEP o gospodarce, Towarzystwo Ekonomistów Polskich. [link](https://tep.org.pl/unia-rynkow-kapitalowych/)

## Research papers:
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
