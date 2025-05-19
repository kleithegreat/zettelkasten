# Positive Operators
**Definition**: An operator $T \in \mathcal{L}(V)$ is called *positive* if $T$ is [[self_adjoint_operators|self-adjoint]] and $$ \langle Tv, v \rangle \geq 0 $$ for all $v \in V$.

If $V$ is complex, the requirement that $T$ is self-adjoint can be dropped.

Let $T \in \mathcal{L}(V)$ be a positive operator. The following are equivalent:
- $T$ is self-adjoint and all [[eigenvalue|eigenvalues]] of $T$ are non-negative.
- With respect to some [[orthonormal_bases|orthonormal basis]] of $V$, the matrix of $T$ is diagonal with non-negative entries.
- $T$ has a positive [[square_root|square root]].
- $T$ has a self-adjoint square root.
- $T = R^*R$ for some $R \in \mathcal{L}(V)$.

Each positive operator has ONLY ONE positive square root.

For a positive operator $T$, $\sqrt{T}$ is the unique positive square root of $T$.

If $T$ is a positive operator and $\langle Tv, v \rangle = 0$ for some $v \in V$, then $v = 0$.