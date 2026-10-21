---
title: "Accelerating the Krusell-Smith Method"
collection: publications
category: working_paper
permalink: /publication/2026-02-17-accelerating-krusell-smith
excerpt: 'This paper accelerates the Krusell-Smith method through policy precomputation, extends the approach using neural networks, and revisits aggregate comovement after uncertainty shocks.'
date: 2026-02-17
keywords:
  - Krusell-Smith Method
  - Policy Precomputation
  - Heterogeneous Agent Models
  - Neural Networks
  - Aggregate Uncertainty
  - Nonconvex Adjustment Costs
  - Computational Economics
  - Macroeconomics
  - Numerical Methods
description: "Policy precomputation accelerates the Krusell-Smith method, with a neural-network extension for larger models and an application showing how finite Frisch elasticity generates aggregate comovement after a pure uncertainty shock."
award: "Finalist, SCE Student Paper Award, CEF Conference"
version_note: "Revised October 21, 2026."
#published: false
show_date: false
#venue: 'GitHub Journal of Bugs'
paperurl: 'https://YoshiyaYokomoto.github.io/files/Acc_KS-main.pdf'
appendixurl: 'https://YoshiyaYokomoto.github.io/files/Acc_KS-appendix.pdf'
#citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

This paper substantially accelerates the Krusell-Smith method, particularly the simulation stage in models with nontrivial market-clearing conditions. By precomputing agents' optimal responses to different prices, the method eliminates the need to repeatedly solve their decision problems during simulation. In the Bloom et al. (2018) model, the proposed grid-based method reduces simulation time from 290 minutes to 1.5 minutes and total computation time from approximately four days to 108 minutes. Because grid-based precomputation becomes costly as the number of states and equilibrium prices increases, I extend the approach using neural networks with a discrete-continuous policy representation that accommodates (S,s)-type adjustment rules.

I then use the method to revisit aggregate comovement after a pure uncertainty shock in the Bloom et al. (2018) model. While the original specification fails to generate simultaneous declines in output, consumption, investment, and employment on impact, allowing for a finite Frisch elasticity restores this comovement.
