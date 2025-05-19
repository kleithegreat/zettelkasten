# Normal Operators
**Definition**: An operator on an inner product space is called *normal* if it commutes with its adjoint.
In other words, $T \in \mathcal{L}(V)$ is normal if $TT^* = T^*T$.

Every [[self_adjoint_operators|self-adjoint]] operator is normal, but not every normal operator is self-adjoint.

$T$ is normal if and only if $Tv$ and $T^*v$ have the same [[norms|norm]] for all $v \in V$.

Properties of normal operators:
- $\text{null}\;T = \text{null}\; T^*$
- $\text{range}\;T = \text{range}\; T^*$
- $V = \text{null}\;T \oplus \text{range}\;T$
- $T - \lambda I$ is normal for all $\lambda \in \mathbb{F}$
- If $v \in V$ and $\lambda \in \mathbb{F}$, then $Tv = \lambda v$ if and only if $T^*v = \overline{\lambda}v$.

[[eigenvector|Eigenvectors]] of distinct eigenvalues of a normal operator are orthogonal.

If $\mathbb{F} = \mathbb{C}$ and $T \in \mathcal{L}(V)$, $T$ is normal if and only if there exist [[commuting_operators|commuting]] self-adjoint operators $A$ and $B$ such that $T = A + iB$.