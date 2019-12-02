---
title: "I will present my work on non-reversible jump algorithms at Bayes Comp 2020"
collection: talks
type: # "Talk"
permalink: /talks/2020-01-07-Bayescomp
venue: "Reitz Union, University of Florida"
excerpt: 'Click [here](https://philippegagnonphd.github.io/website/talks/2020-01-07-Bayescomp) for the abstract.'
date: 2020-01-07
location: "Gainesville, Florida, USA"
---

**Abstract:** Non-reversible Markov chain Monte Carlo methods often outperform their reversible counterparts in terms of asymptotic variance of ergodic averages and mixing properties. Lifting the state-space ([Chen et al., 1999](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.68.1147); [Diaconis et al., 2000](https://projecteuclid.org/download/pdf_1/euclid.aoap/1019487508)) is a generic technique for constructing such samplers. The idea is to think of the random variables we want to generate as position variables and to associate to them direction variables so as to design Markov chains which do not have the diffusive behaviour often exhibited by reversible schemes. In this paper, we explore the benefits of using such ideas in the context of Bayesian model choice for nested models, a class of models for which the model indicator variable is an ordinal random variable. By lifting this model indicator variable, we obtain non-reversible jump algorithms, a non-reversible version of the popular reversible jump algorithms introduced by [Green (1995)](https://www2.stat.duke.edu/~scs/Courses/Stat376/Papers/TransdimMCMC/GreenRevJump.1995.pdf). This simple algorithmic modification provides samplers which can empirically outperform their reversible counterparts at no extra computational cost. The code to reproduce all experiments is available online.

For more information about the conference see this [website](http://users.stat.ufl.edu/~jhobert/BayesComp2020/Conf_Website/).