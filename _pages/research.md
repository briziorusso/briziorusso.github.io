---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research interests revolve around augumenting human decision making with AI. This involves drawing the most relevant relationships from data. Current practices in data-driven decisioning adopts models that span from regression to neural networks and ensemble trees, this although powerful and mostly informative only capture correlations in the data. My PhD project, supervised by Prof. Francesca Toni at Imperial College, tries to address this issue and focuses on creating transparent techniques for causal discovery, using argumentation. Causal discovery is about drawing a graph of the relationships influencing an observed effect. Argumentation is a form of non-monotonic reasoning useful for resolving coflicts in a debate. We are creating a system that allows humans and machines to debate about causality. This will allow deisions to be based on cause-effect relationships, hence giving decision makers the levers to change things.

# Talks & Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

