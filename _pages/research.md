---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research sits at the intersection of causal discovery, causal representation learning, computational argumentation, and trustworthy AI. I study how causal structure can be learned from data and knowledge, represented in ways that support reasoning, and made open to explanation, challenge, and revision. The broader goal is to develop causal AI that helps people make better decisions in high-stakes domains such as healthcare, finance, and public policy.

My PhD thesis, supervised by [Prof. Francesca Toni](https://www.imperial.ac.uk/people/f.toni) and titled *Causal Discovery for Trustworthy Artificial Intelligence*, introduced transparent methods for causal discovery based on computational argumentation. This work led to Causal ABA, which represents statistical evidence and domain knowledge as defeasible arguments. Conflicts between causal claims can therefore be inspected and resolved rather than hidden behind a single output graph.

I subsequently served as co-investigator and technical lead on the ERC Proof of Concept project [CArLA: Causal Argumentative Learning Assistant](https://cordis.europa.eu/project/id/101189053). The completed project developed Causal ABA into an interactive framework for transparent, explainable, and contestable causal discovery, combining attributable evidence from data, language models, and domain experts. Its outputs and publications are available on the [project website](https://clarg-group.github.io/CArLA/), and the [CArLA demonstration](https://clarg-group.github.io/CArLA/demo/) shows how users can inspect evidence, challenge causal claims, resolve conflicts, and trace the resulting revisions.

My current research focuses on three connected directions:

- investigating the interaction between causal discovery and causal representations, including how learned representations can support the discovery of causal structure and how causal structure can guide representation learning;
- equipping Causal ABA with stronger statistical guarantees, so that its conclusions account explicitly for uncertainty and the reliability of evidence learned from finite data; and
- extending its explainability and contestability capabilities by learning causal mechanisms as defeasible rules that people can inspect, challenge, and revise.

Together, these strands aim to connect statistical causal learning with symbolic reasoning, producing causal models whose evidence, mechanisms, and limitations remain visible to the people who rely on them.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include publication-list.html %}

