# Normal Subgroup
**Definition**: Let $H$ be a [[subgroup]] of $G$. We say that $H$ is a *normal* subgroup of $G$ if for all $g \in G$, $gH = Hg$. If $H$ is a normal subgroup of $G$, we write $H \trianglelefteq G$.

The following are equivalent conditions for $H$ to be a normal subgroup of $G$:
- $ghg^{-1} \in H$ for all $g \in G$ and $h \in H$.
- $gHg^{-1} = H$ for all $g \in G$.
- There is a [[group_homomorphism|homomorphism]] $\phi: G \to G'$ such that $\ker(\phi) = H$. Related: [[first_isomorphism_theorem|First Isomorphism Theorem]].
- $gH = Hg$ for all $g \in G$.

Let $\phi: G \to G'$ be a group homomorphism. If $N$ is a [[normal_subgroup|normal subgroup]] of $G$, then $\phi[N] \trianglelefteq \phi[G]$. Also, if $N' \trianglelefteq \phi[G]$, then $\phi^{-1}[N'] \trianglelefteq G$.