---
title: "I will present my work on nonreversible jump algorithms at Bayes Comp 2020"
collection: talks
type: # "Talk"
permalink: /talks/2019-08-08-Bayescomp
venue: "Reitz Union, University of Florida"
date: 2020-01-07
location: "Gainesville, Florida, USA"
---

Abstract (for more information about the conference see this [website](http://users.stat.ufl.edu/~jhobert/BayesComp2020/Conf_Website/)): It is now well known that nonreversible Markov chain Monte Carlo methods often outperform their reversible counterparts. Lifting the state space (Chen et al. (1999)) has proved to be a successful technique for constructing such samplers relying on nonreversible Markov chains. The idea is to see the random variables that we wish to generate as position variables to which we associate velocity (or direction) variables, doubling the size of the state space. At each iteration of such samplers, the positions evolve deterministically as a function of the directions, and this is followed by a possible update of the latter. This direction assisted scheme may induce persistent movements that allow to traverse the state space more quickly, compared with the traditional methods producing chains with diffusive patterns. This explains the gain in efficiency. Directions playing a central role, the technique can only be employed to explore state spaces for which this concept is well defined. In this paper, we introduce samplers that we call nonreversible jump algorithms that can be applied to simultaneously achieve model selection and parameter estimation, in situations where the family of models considered forms a sequence of nested models; there thus exists a natural order among the models, and therefore, directions. These samplers are constructed by modifying reversible jump algorithms after having lifted the part of the state space associated with the model indicator. We demonstrate their correctness and show that they compare favourably to their reversible counterpart using both theoretical arguments as well as numerical experiments. We address implementation challenges, facilitating application by users.
P.S.: the preprint will soon be on ArXiv.
