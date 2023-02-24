---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Under Review

**Information and Ranked Choice Voting**, _Theodoros Ntounias_

Under review at the Election Law Journal

_Draft: February 6th 2023_

Does ranked choice voting (RCV) change the information search behavior of voters? The answer to this question is important in the context of the proposed benefits of RCV, which I argue are conditional on voters broadening their information search. Results of a nationally diverse survey sample experiment indicate that voters do not adapt their information search and retention behaviors, nor do they spend more cognitive effort in the process of voting.

[Download paper here](http://tdounias.github.io/files/rcv_02_2023.pdf)

## Work in Progress

**Globalization and Political Ambiguity**, _Theodoros Ntounias, Christina J. Schneider, and Robert Thomson_

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
