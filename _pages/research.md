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

**Cutting Off the Respirator: Aspiring Autocrats and Subnational Autonomy**, _Theodoros Ntounias_

Dissertation Project

Recent scholarship has increasingly argued that when countries face democratic erosion at the hands of aspiring autocrats, one of the most important bulwarks against backsliding is local government. However, the degree to which resilience can manifest at the subnational level is dependent on the ability of local officials to effectively use fiscal resources, in order to convince voters of their competence and build their power. I argue that aspiring autocrats target local revenue independence, reducing the autonomy of their opponents while increasing the resources at the disposal of their allies. I focus on the case of democratic erosion in Poland (2015-2023), presenting extensive descriptive evidence of horizontal reductions in local autonomy, but also of an opportunity structure for selective attacks on opposition municipalities. To investigate causally, I use data on municipal finances and electoral results to conduct a close elections regression discontinuity design. I find a significant effect of electing an aspiring autocrat government-aligned mayor over their opponent, on municipal level measures of autonomous revenue and decentralization, indicating that copartisans are shielded from horizontal reductions in local autonomy. This paper presents a contribution to the literature on democratic resilience, but also to the wider literature on fiscal decentralization and local government autonomy, by establishing how aspiring autocrats take advantage of subnational fiscal policy to erode democracy.

**Globalization and Political Ambiguity**, _Theodoros Ntounias, Christina J. Schneider, and Robert Thomson_

Working paper available courtesy of the UC IGCC [here](https://escholarship.org/uc/item/0050h951)

_Under review at Comparative Political Studies_

Despite the centrality of promissory representation in the study of democracy, we know little about how concerns about voters' retrospective evaluation of political parties' ability to keep campaign promises affects the form of promissory representation by political parties. We argue that political parties rely on strategic ambiguity during election campaigns to evade sanctioning by voters in future elections. We analyze the effects of globalization on strategic ambiguity of 44 political parties in 293 English language party platforms across six countries between 1970 and 2019, and find robust support for our expectations. 

**Private Welfare in the Workplace and Support for Social Insurance**, _John S. Ahlquist, Theodoros Ntounias_

There is a long-standing argument that public welfare and social insurance crowds out private savings and charity. There is also a newer set of arguments that private resources (home equity, credit) may dampen voters' support for public insurance programs and redistributive taxation. We investigate the "substitution hypothesis" in the context of a novel set of workplace mutual aid arrangements--Employee Hardship Funds (EHFs). EHFs enable employers to distribute emergency cash to their workers using donations pooled from employees themselves. Hundreds of major US firms now operate these programs. We use three original surveys---including two matched to workers at specific employers with EHFs and including experiments.We find that state-level generosity in the social safety net is unrelated to worker knowledge of and support for EHFs. Experimental manipulation of EHF salience among workers at two large retailers indicates that EHFs do not displace support for public unemployment insurance or government emergency aid, regardless of the generosity of the EHF program. EHFs, as a workplace mutual aid arrangement, and government social insurance programs appear unconnected in the minds of workers.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
