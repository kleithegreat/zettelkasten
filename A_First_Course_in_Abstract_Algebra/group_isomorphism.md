# Group Isomorphism
**Definition**: Let $\langle G_1, *_1 \rangle$ and $\langle G_2, *_2 \rangle$ be [[group|groups]] and $f: G_1 \to G_2$. We say that $f$ is a *group isomorphism* if:
1. $f$ is a bijection (one-to-one and onto).
2. $f$ is a [[group_homomorphism|homomorphism]], i.e., for all $a, b \in G_1$, $f(a *_1 b) = f(a) *_2 f(b)$.

Let $G = H \times K$ be the [[direct_product_groups|direct product]] of groups $H$ and $K$. Then $\overline{H} = \{(h, e_K) \mid h \in H\}$ is a [[normal_subgroup|normal subgroup]] of $G$. Also $G/\overline{H} \cong K$ naturally, and $G/\overline{K} \cong H$ naturally. The isomorphism is given by the projection map $\pi: H \times K \to K$ defined by $\pi(h, k) = k$.