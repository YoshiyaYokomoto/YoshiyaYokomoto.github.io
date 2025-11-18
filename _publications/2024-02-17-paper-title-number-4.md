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

This paper introduces a novel solution method for heterogeneous firm models with aggregate uncertainty that significantly reduces computational time while maintaining solution accuracy. The core innovation involves approximating the policy function with a neural network that includes the equilibrium price as a state variable. This strategy directly tackles the fundamental computational bottleneck of repeated market-clearing equilibrium price calculations during simulation, leveraging the neural network's ability to handle the resulting high-dimensional state space and overcome the curse of dimensionality. Applied to seminal models in the literature, including Khan and Thomas (2008) and Bloom et al. (2018), this approach achieves speed improvements of up to 50x. By maintaining the skeleton of established solution techniques while replacing key components with neural network approximations, my approach remains transparent and accessible to researchers already familiar with standard heterogeneous agent modeling techniques, opening new possibilities for analyzing complex firm dynamics with realistic computational resources.
