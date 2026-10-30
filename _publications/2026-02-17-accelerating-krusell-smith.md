---
title: "Accelerating the Krusell-Smith Method"
collection: publications
category: working_paper
permalink: /publication/2026-02-17-accelerating-krusell-smith
excerpt: 'This paper develops a neural-network-based Krusell-Smith method and resolves the aggregate comovement puzzle after uncertainty shocks with a finite Frisch elasticity, even under separable preferences.'
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
description: "A neural-network-based Krusell-Smith method reduces runtime in the Bloom et al. (2018) model from 6,141 to 183 minutes and shows how a finite Frisch elasticity restores aggregate comovement after a pure uncertainty shock, even under separable preferences."
award: "Finalist, SCE Student Paper Award, CEF Conference"
version_note: "Revised October 30, 2026."
#published: false
show_date: false
#venue: 'GitHub Journal of Bugs'
paperurl: 'https://YoshiyaYokomoto.github.io/files/Acc_KS-main.pdf'
appendixurl: 'https://YoshiyaYokomoto.github.io/files/Acc_KS-appendix.pdf'
#citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

This paper develops a neural-network-based Krusell-Smith (NN-KS) method for heterogeneous firm models with aggregate uncertainty. By conditioning firms' policies on trial prices, NN-KS replaces repeated optimization during market-clearing searches with policy evaluation. A discrete-continuous policy architecture preserves exact inaction and captures discontinuous (S,s)-type adjustment rules. In the baseline Bloom et al. (2018) model, NN-KS reduces total computation time from 6,141 minutes (approximately four days) to 183 minutes.

I then use NN-KS to extend the model with a finite Frisch elasticity, two equilibrium prices, and lagged aggregate employment as an additional state. Solved in approximately 200 minutes, the extended model generates simultaneous declines in output, consumption, investment, and employment after a pure uncertainty shock, even under separable preferences. Falling real wages cushion the contractions in labor and investment, restoring aggregate comovement.
