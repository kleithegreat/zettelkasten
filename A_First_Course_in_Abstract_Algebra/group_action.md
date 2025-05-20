# Group Action on a Set
**Definition**: Let $X$ be a set and $G$ a [[group]]. An *action of $G$ on $X$* is a map $*: G \times X \to X$ such that:
1. $e_G x = x$ for all $x \in X$
2. $(g_1 g_2) x = g_1 (g_2 x)$ for all $g_1, g_2 \in G$ and $x \in X$.
Under these conditions, $X$ is a *$G$-set*.

Let $X$ be a $G$-set. For each $g \in G$, the function $\sigma_g: X \to X$ defined by $\sigma_g(x) = gx$ for $x \in X$ is a permutation of $X$. Also, the map $\phi: G \to S_X$ defined by $\phi(g) = \sigma_g$ is a [[group_homomorphism|homomorphism]] with the property that $\phi(g)(x) = gx$.
Related: [[permutation_group|permutation group]].

Let $X$ be a $G$-set and let $x \in X$. Then $|Gx| = (G : G_x)$. If $|G|$ is finite, then $|Gx| is a divisor of $|G|$. Related: [[orbit]], [[isotropy_subgroup|isotropy subgroup]].

Let $G$ be a group with $p^n$ elements where $p$ is a prime. If $X$ is a $G$-set, then $|X| \equiv |X_G| \pmod{p}$.