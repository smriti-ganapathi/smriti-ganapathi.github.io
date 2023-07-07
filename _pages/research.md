---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Work in progress
======

* The Dynamics of Coercive Control in Intimate Partner Violence
  Coercive control, a pattern of psychological control and intimidation, is believed to be widely prevalent in cases of intimate partner violence (IPV). However,     the definition and measurement of coercive control to ascertain true prevalence remains a challenge. In this study, I develop and validate a measure of coercive    control using granular, IPV incident-level police data from the United Kingdom. I also investigate how criminal charges affect the use of coercive control and      physical violence by perpetrators. Do perpetrators shift from using more obvious forms of physical violence to more subtle forms of coercive control, upon          facing criminal sanctions? Or do the two go hand-in-hand? Results indicate that criminal charges reduce both physical violence and coercive control, suggesting     that the two are used together as tools of manipulation and control. This also implies that pressing charges can lower the risk of repeat abuse in IPV cases in     this setting.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
