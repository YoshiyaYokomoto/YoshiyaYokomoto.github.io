---
title: "A Fast Deep Learning Solution for Market Clearing in Heterogeneous Agent Models"
collection: publications
category: working_paper
#permalink: /publication/2024-02-17-paper-title-number-4
#excerpt: 'This paper is about fixing template issue #693.'
date: 2025-04-02
#published: false
show_date: false
#venue: 'GitHub Journal of Bugs'
paperurl: 'http://YoshiyaYokomoto.github.io/files/Yokomoto_draft_10.pdf'
#citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

This paper proposes a novel global solution method that sharply reduces the computational
burden of heterogeneous agent models with aggregate uncertainty, where market prices are determined implicitly. The main bottleneck in such models is the repeated search for the market-clearing equilibrium price within each simulation period. To overcome this issue, the core of the method is to approximate the policy function with neural networks that incorporates the equilibrium price as a state variable. 
Once trained, this price-conditional policy function eliminates the need for repeated optimization during equilibrium searches, directly resolving the bottleneck. In addition, the neural network approach mitigates the curse of dimensionality from an expanded state space and is flexible enough to handle non-smooth policy functions, such as (S-s) rules arising from fixed adjustment costs.
Applying the method to the models of Khan and Thomas (2008) and Bloom et al. (2018)
demonstrates substantial improvements in speed while preserving accuracy. For example, the
Bloom et al. (2018) model, which requires six days under the Krusell-Smith method, can be
solved in just 59 minutes. A further advantage is that the method preserves the skeleton of
existing solution techniques like the Krusell-Smith algorithm, making it straightforward for
researchers to understand and implement.
