---
title: 
description: 
aliases: 
draft: false
date: 
tags:
---


The Lebesgue integral of a function $f: \mathbb{R} \rightarrow \mathbb{R}$ over a set $E \subseteq \mathbb{R}$ is denoted by $\int_E f \, d\mu$ and is defined in terms of simple functions that approximate $f$ from below. For non-negative $f$, it is the supremum of the integrals of simple functions that are less than or equal to $f$, and for general $f$, it is the difference of the integrals of its positive and negative parts if at least one of them is finite.

The Lebesgue integral of a non-negative function $f$ over a set $E$ is defined as:

$$ \int_E f \, d\mu = \sup \left\{ \int_E \varphi \, d\mu \, \middle| \, \varphi \text{ simple and } \varphi \leq f \text{ on } E \right\} $$

For a general function $f$ that takes on both positive and negative values, its Lebesgue integral is defined as:

$$ \int_E f \, d\mu = \int_E f^+ \, d\mu - \int_E f^- \, d\mu $$

where $f^+$ and $f^-$ are the positive and negative parts of $f$, and both integrals on the right-hand side are defined as above. Specifically, if $\int_E f^+ \, d\mu$ or $\int_E f^- \, d\mu$ is infinite, the integral of $f$ is defined if and only if one of them is finite, in which case the integral is taken to be $\pm \infty$ correspondingly.


# References
