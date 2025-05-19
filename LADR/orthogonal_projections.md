# Orthogonal Projections
**Definition**: Suppose $U$ is a finite-dimensional subspace of $V$. The *orthogonal projection* of $V$ onto $U$ is the operator $P_U \in \mathcal{L}(V)$ defined as follows: For each $v \in V$, write $v = u + w$ where $u \in U$ and $w \in U^\perp$. Then $P_U v = u$.

Basic properties of orthogonal projections:
- $P_U \in \mathcal{L}(V)$
- $P_U u = u$
- $P_U w = 0$
- $\text{range}\;P_U = U$
- $\text{null}\;P_U = U^\perp$
- $v - P_U v \in U^\perp$
- $P_U^2 = P_U$
- $\|P_U v\| \leq \|v\|$
- if $e_1, \ldots, e_m$ is an orthonormal basis for $U$ and $v \in V$, then
$$ P_U v = \langle v, e_1 \rangle e_1 + \langle v, e_2 \rangle e_2 + \cdots + \langle v, e_m \rangle e_m $$

Related: [[orthogonal_complements|orthogonal complements]], [[orthonormal_bases|orthonormal bases]].

Riesz representation theorem revisited: Suppose $V$ is finite dimensional. For each $v \in V$, define $\phi_v \in V'$ by
$$ \phi_v(u) = \langle u, v \rangle $$
for each $u \in V$. Then $v \mapsto \phi_v$ is a linear isomorphism between $V$ and $V'$.