# Orthogonal Complements
**Definition**: If $U$ is a subSET of $V$, the *orthogonal complement* of $U$ denoted by $U^\perp$ is the set of all vectors in $V$ that are orthogonal to every vector in $U$.

Basic properties of orthogonal complements:
- If $U$ is a subset of $V$, then $U^\perp$ is a [[subspaces|subspace]] of $V$.
- $\{0\}^\perp = V$.
- $V^\perp = \{0\}$.
- If $U$ is a subset of $V$, then $U \cap U^\perp = \{0\}$.
- If $G$ and $H$ are subsets of $V$ and $G \subseteq H$, then $H^\perp \subseteq G^\perp$.

If $U$ is a finite-dimensional subspace of $V$, then $V = U \oplus U^\perp$. Related: [[direct_sum|direct sum]].

If $V$ is finite-dimensional and $U$ is a subspace of $V$, then $\dim U^\perp = \dim V - \dim U$. Related: [[dimension]].

Imporant: $U = (U^\perp)^\perp$.

If $U$ is a finite-dimensional subspace of $V$, then $U^\perp = \{0\}$ if and only if $U = V$.