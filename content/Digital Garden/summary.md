Let $(\mathbb{X},\Sigma, \mu)$ be a measure space, $X \in \Sigma, \forall n \in \mathbb{N}, \forall x \in X,$
FL: $f_{n}:X \rightarrow [0,\infty]$ are $(\Sigma ,\operatorname {\mathcal {B}} _{\mathbb {R} _{\geq 0}})$-measurable, $\set{f_{n}} \rightarrow f = \liminf f_{n}(x)$ pointwise a.e. $\Rightarrow  \int_{X}f d\mu \leq \liminf \int_{X}f_{n}d\mu \leq \infty$
 BCT: $\mu (X) < \infty$, $\set{f_{n}}$ measurable and uniformly pointwise bounded,  $f_{n}(x) \leq M$, $\set{f_{n}} \rightarrow f$ pointwise $\Rightarrow \lim\limits_{{n \to \infty}} \int_{X}f_{n}d\mu = \int_{X} f d\mu$
 MCT: $f_{n}:X \rightarrow [0,\infty]$ are $(\Sigma ,\operatorname {\mathcal {B}} _{\mathbb {R} _{\geq 0}})$-measurable, and $f_{n}(x) \leq f_{n+1}(x)$, $\set{f_{n}} \rightarrow f$ pointwise a.e. $\Rightarrow \lim\limits_{{n \to \infty}} \int_{X}f_{n}d\mu = \int_{X} f d\mu$
 LDCT: $\forall x \in X, f_{n}:X \rightarrow \mathbb{C}$ are measurable, $\int_{X} |g| d\mu < \infty$, $|f_{n} | \leq g$, $\set{f_{n}} \rightarrow f$ pointwise a.e. $\Rightarrow \int_{X} |f| d\mu < \infty$ and $\lim\limits_{{n \to \infty}} \int_{X}f_{n}d\mu = \int_{X} f d\mu$
 VCT: $\mu (X) < \infty$, $\set{f_{n}}$ uniformly integrable, $\set{f_{n}} \rightarrow f$ pointwise a.e. $\Rightarrow f$ integrable and $\lim\limits_{{n \to \infty}}  \int_{X}f_{n}d\mu = \int_{X} f d\mu$

ET: For a finite measure space $E$ and a pointwise convergent sequence of measurable functions $\{f_n\}$ to a real-valued function $f$ on $E$, for any $\varepsilon > 0$, there exists a closed subset $F \subseteq E$ such that $\{f_n\} \rightarrow f$ uniformly on $F$ and $m(E \setminus F) < \varepsilon$.
ETLem: for each $\eta > 0$ and $\delta > 0$, there exists a measurable subset $A \subseteq E$ and an index $N$ such that $|f_n - f| < \eta$ for all $n \geq N$ and $m(E \setminus A) < \delta$.

The [[Cantor set]] $C$ is the intersection of a descending sequence of closed sets, defined as a disjoint union of $2^k$ closed intervals each of length $1/3^k$. It is a closed, uncountable set of measure zero.   There exists a measurable set, a subset of the Cantor set, that is not a Borel set.

 **[[Cantor-Lebesgue Function]]:** Defined on $[0,1]$, this function is continuous, increasing, and maps $[0,1]$ onto $[0,1]$. Its derivative exists and is zero on the complement of the Cantor set in $[0,1]$, which has measure 1.

  Let $\psi(x) = \varphi(x) + x$ for all $x \in [0, 1]$, where $\varphi$ is the Cantor-Lebesgue function. Then $\psi$ is strictly increasing and continuous, mapping $[0,1]$ onto $[0,2]$, the Cantor set $C$ onto a measurable set of positive measure, and a measurable subset of $C$ onto a nonmeasurable set.

The Lebesgue integral of a non-negative function $f$ over a set $E$ is defined as:

$$ \int_E f \, d\mu = \sup \left\{ \int_E \varphi \, d\mu \, \middle| \, \varphi \text{ simple and } \varphi \leq f \text{ on } E \right\} $$

For a general function $f$ that takes on both positive and negative values, its Lebesgue integral is defined as:

$$ \int_E f \, d\mu = \int_E f^+ \, d\mu - \int_E f^- \, d\mu $$

where $f^+$ and $f^-$ are the positive and negative parts of $f$, and both integrals on the right-hand side are defined as above. Specifically, if $\int_E f^+ \, d\mu$ or $\int_E f^- \, d\mu$ is infinite, the integral of $f$ is defined if and only if one of them is finite, in which case the integral is taken to be $\pm \infty$ correspondingly.


