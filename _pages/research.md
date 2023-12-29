---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research interests revolve around augumenting human decision making with AI. This involves evaluating the interaction of the desired outcome with its context. Current practices in data-driven decisioning adopt models that span from regression to neural networks and ensemble trees which, although powerful and mostly informative, only capture correlations in the data. Correlation is hardly enough when trying to understand the effect of actions. What decision-makers need is causality.

My PhD project, supervised by [Prof. Francesca Toni](https://www.imperial.ac.uk/people/f.toni) at Imperial College, works towards creating transparent techniques for causal discovery and its use in machine learning predictions, leveraging argumentation. Causal discovery is about drawing a graph of the relationships influencing an observed phenomenon. Argumentation is a form of non-monotonic reasoning useful for resolving coflicts in a debate. We are creating a system that allows humans and machines to debate about causality. This will highlight cause-effect relationships, giving decision-makers the levers to drive the outcomes they seek.


# Talks & Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} 

