---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Publications

[**Information and Ranked Choice Voting**](https://doi.org/10.1089/elj.2022.0052), _Theodoros Ntounias_

_Election Law Journal: Rules Politics and Policy_

Does ranked choice voting (RCV) change the information search behavior of voters? The answer to this question is important in the context of the proposed benefits of RCV, which I argue are conditional on voters broadening their information search. Results of a nationally diverse survey sample experiment indicate that voters do not adapt their information search and retention behaviors, nor do they spend more cognitive effort in the process of voting.

[Download paper here](http://tdounias.github.io/files/rcv_05_2023.pdf)

## Work in Progress

**Recentralization as an Aspiring Autocrat Strategy**, _Theodoros Ntounias_

Dissertation Project

Recent scholarship on democratic backsliding focuses on the conditions under which anti-pluralist governments (Lührmann, Medzihorsky, and Lindberg 2021) come to power, and the strategies they employ to secure their control, focusing especially on the aggrandizement of their executive power (Bánkuti, Halmai, and Scheppele 2012; Haggard and Kaufman 2021; Stenberg, Rocco, and Farole 2022). Novel research has also noted the importance of subnational resilience (Jakli and Stenberg 2011; Kjaer 2012; Farole 2020) as a pathway to opposing autocratization. In my dissertation book project which focuses on the context of European democracies, I argue that anti-pluralist governments implement fiscal recentralization in order to minimize local resistance while arming themselves with resources for aggrandizement, with the goal of securing political dominance. I develop a theory of recentralization as a strategy for backsliding, which I intend to test using a cross-national synthetic control group regression design, alongside a set of case studies on countries such as Hungary, Poland, Serbia, and Turkey. With this design I intend to establish (1) the general trend of recentralization across backsliding democracies and (2) the impact that recentralization has on backsliding and opposition contestation. Apart from my contribution to the increasingly varied literature on subnational democratic backsliding and local resilience, I additionally intend to bridge the gap between a vibrant political economy literature on regime type as a determinant of fiscal federalism, and the modern backsliding literature. 

**Globalization and Political Ambiguity**, _Theodoros Ntounias, Christina J. Schneider, and Robert Thomson_

_Under Review at the American Political Science Review_

Despite the centrality of promissory representation in the study of democracy, we know little about how concerns about voters' retrospective evaluation of political parties' ability to keep campaign promises affects the form of promissory representation by political parties. We argue that political parties rely on strategic ambiguity during election campaigns to evade sanctioning by voters in future elections. We analyze the effects of globalization on strategic ambiguity of 44 political parties in 293 English language party platforms across six countries between 1970 and 2019, and find robust support for our expectations. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
