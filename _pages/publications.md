---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Work in Progress
======

The Effect of Judicial Decisions on Policy Narratives

Abstract
How do judicial decisions influence political discourse, particularly in areas as contentious as abortion rights? This study investigates how the overturning of Roe v. Wade affected the narrative strategies of U.S. representatives on social media, with a focus on variations by party affiliation and geographic context due to state-level trigger laws. Employing supervised machine learning for text classification and generalized linear mixed models, this research analyzed a dataset of abortion-related tweets from U.S. representatives throughout 2022. The study found a significant shift toward narratives of decline across both major political parties following the overturning, with variations evident around critical events and influenced by state-level trigger laws. These findings contribute to narrative policy analysis and political communication and highlight the strategic use of narratives in response to judicial decisions, the complex connection between political narratives and electoral strategies, and the complex role of geographic and legislative contexts in shaping political discourse.


