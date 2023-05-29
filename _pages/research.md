---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Under Review

**Information and Ranked Choice Voting**, _Theodoros Ntounias_

Under review at the Election Law Journal

_Draft: May 29th 2023_

Does ranked choice voting (RCV) change the information search behavior of voters? The answer to this question is important in the context of the proposed benefits of RCV, which I argue are conditional on voters broadening their information search. Results of a nationally diverse survey sample experiment indicate that voters do not adapt their information search and retention behaviors, nor do they spend more cognitive effort in the process of voting.

[Download paper here](http://tdounias.github.io/files/rcv_05_2023.pdf)

## Work in Progress

**Globalization and Political Ambiguity**, _Theodoros Ntounias, Christina J. Schneider, and Robert Thomson_

Working Paper

Despite the centrality of promissory representation in the study of democracy, we know little about how concerns about voters' retrospective evaluation of political parties' ability to keep campaign promises affects the form of promissory representation by political parties. We argue that political parties rely on strategic ambiguity during election campaigns to evade sanctioning by voters in future elections. We analyze the effects of globalization on strategic ambiguity of 44 political parties in 293 English language party platforms across six countries between 1970 and 2019, and find robust support for our expectations. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
