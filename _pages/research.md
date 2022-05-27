---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Broadly my research interests fall within two main areas: Explainable AI and Statistical Learning. I am of the view that statistical learning is explainable, for how complex it might be, because it reduces to an algorithm that will give you an output given a set of inputs. I'm on a quest to expose the explainability of the different types of learning algorithms. I believe that doing so will increase their power, make them more correct and finally provide people with knowledge extracted from data.

In particular, my PhD project (supervised by [Francesca Toni](https://www.doc.ic.ac.uk/~ft/) at Imperial College London) is about improving the robustness and transparency of black box machine learning (ML) models. We are planning to do that by making ML model respect imparted and discovered causal knowledge and then use this as the basis of argumentative explanations. Explainable AI (XAI) is getting a lot of attention because it allows people to understand models and trust their behaviour. That is my aim, make ML models more robust and trustworthy through causality and argumentative explanations that open these black boxes.

# Talks & Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

