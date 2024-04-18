---
title: 
description: 
aliases: [MCT]
draft: false
date:
---

[[mathematics/real analysis/bounded convergence theorem|bounded convergence theorem]]

[[Lebesgue dominated convergence theorem]]
[[Vitali convergence theorem]]

Let $(\mathbb{X},\Sigma, \mu)$ be a measure space, $X \in \Sigma$

 $\forall n \in \mathbb{N}, \forall x \in X, f_{n}:X \rightarrow [0,\infty]$ are $(\Sigma ,\operatorname {\mathcal {B}} _{\mathbb {R} _{\geq 0}})$-measurable, and $f_{n}(x) \leq f_{n+1}(x)$, $\set{f_{n}} \rightarrow f$ pointwise a.e. $\Rightarrow \lim\limits_{{n \to \infty}} \int_{X}f_{n}d\mu = \int_{X} f d\mu$

Pf
- [[Fatou's lemma]]
- monotonicity of integration