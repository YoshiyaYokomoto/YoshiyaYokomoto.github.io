---
title: "Accelerating the Krusell-Smith Algorithm with Deep Learning"
collection: publications
category: working_paper
#permalink: /publication/2024-02-17-paper-title-number-4
#excerpt: 'This paper is about fixing template issue #693.'
date: 2026-02-17
#published: false
show_date: false
#venue: 'GitHub Journal of Bugs'
paperurl: 'http://YoshiyaYokomoto.github.io/files/NN-KS_02.pdf'
#citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

This paper accelerates the Krusell-Smith algorithm for heterogeneous agent models by leveraging deep learning. While the Krusell-Smith method remains the gold standard for its accuracy and ability to handle large shocks and non-linear dynamics, it suffers from a severe computational bottleneck: the stochastic simulation requires finding market-clearing prices numerically in every period, repeatedly solving optimization problems for each price guess until markets clear. I address this bottleneck by approximating value and policy functions with neural networks that include the market-clearing price directly as an input. Once trained, the network instantly evaluates policies for any price through a forward pass, eliminating the need for repeated optimization during simulation. This succeeds because neural networks tame the curse of dimensionality and are flexible enough to handle non-smooth, discontinuous policies arising from fixed adjustment costs, where traditional grid-based methods fail. The implementation is straightforward—simply replace traditional approximations with neural networks while preserving the Krusell-Smith structure—and delivers dramatic results: the \citet{bloom2018} model solves in 102 minutes instead of six days with identical accuracy. The approach applies generally to any heterogeneous agent model with complex market clearing conditions, with advantages growing as model complexity increases.
