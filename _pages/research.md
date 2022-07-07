---
layout: archive
title: "Working Papers"
permalink: /research/
author_profile: true
---

### Information and Ranked Choice Voting

_Draft: July 7th 2022_

Does ranked choice voting (RCV) change the information search behavior of voters? The answer to this question is important in the context of the proposed representational benefits of RCV, which I argue are conditional on voters broadening their information search. Results of a nationally diverse survey sample experiment indicate that voters do not adapt their information search and retention behaviors, nor do they spend more cognitive effort in the process of voting.

[Download paper here](http://tdounias.github.io/files/rcv_07_2022.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
