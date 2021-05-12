---
layout: single
title: "Project"
permalink: /project/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

The big data era represents an opportunity for statistical methods to shine, through applications relevant to a wide spectrum of fields, including actuarial science. In order to seize and make the most out of this opportunity, researchers and practitioners must, however, effectively manage the challenges that big data pose.

Firstly, quantity surely does not imply quality, and data are no exception to this rule. Identifying trends in poor quality data with gross errors is difficult. Methods that are robust against outliers help in this task. One of my research goals is to introduce robust Bayesian models of practical relevance for actuaries. Generalised linear models (GLMs) are, for instance, ubiquitous in general insurance claim modelling. Robust GLMs are a class of models to be proposed. They will have the remarkable characteristic of producing results based solely on the non-outliers in the limit when the outliers move further and further away, while performing similarly to the traditional models in the absence of outliers. The impact of the outliers in fact gradually vanishes, reflecting that at the beginning when they are not so far from the bulk of the data, there is an uncertainty about whether they really are outliers or not. Methods automatically dealing with this uncertainty are particularly valuable in high-dimensional and variable selection problems.

Secondly, proposing complex models handling gross errors is not enough. The numerical methods required for inference must scale with the model complexity and data size to ensure that the statistical procedures are implementable. For this purpose, I will propose automatic non-reversible jump algorithms. These are Markov chain Monte Carlo (MCMC) methods used for approximating integrals with respect to joint posterior distributions of models and their parameters, which allows simultaneous Bayesian variable selection and parameter estimation. Non-reversible methods are known for their better scalability in typical cases, comparatively to their reversible counterparts. This is due to Markov chains with paths characterised by persistent movement that allow to traverse the state space more quickly and prevent the diffusive behaviour often exhibited by reversible schemes. This translates into less autocorrelations, which implies less iterations to obtain independent samples from the posterior distributions. The results are thus closer to regular Monte Carlo, which is the ultimate MCMC goal.

Robust statistical models together with automatic and efficient numerical methods for automated inference result in: robust and efficient statistical learning algorithms. The advantage of statistical procedures (over typical machine learning algorithms for instance) is that they allow risk and uncertainty quantification. This quantification is at the core of actuaries’ role and allows to issue statements containing rich probabilistic descriptions about the capacity of insurance firms to pay for future claims.