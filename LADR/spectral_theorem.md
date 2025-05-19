# Spectral Theorem

## Real Spectral Theorem

Suppose $T \in \mathcal{L}(V)$ is [[self_adjoint_operators|self-adjoint]] and $b, c \in \mathbb{R}$ such that $b^2 \leq 4c$. Then $T^2 - bT + cI$ is [[invertibility|invertible]].

Suppose $T \in \mathcal{L}(V)$ is self-adjoint. Then the [[minimal_polynomial|minimal polynomial]] of $T$ equals $(z - \lambda_1) \cdots (z - \lambda_m)$ for some $\lambda_1, \ldots, \lambda_m \in \mathbb{R}$.

**Statement**: Suppose $\mathbb{F} = \mathbb{R}$ and $T \in \mathcal{L}(V)$. Then the following are equivalent:
- $T$ is self-adjoint.
- $T$ has a diagonal matrix with respect to some [[orthonormal_bases|orthonormal basis]] of $V$.
- $V$ has an orthonormal basis consisting of [[eigenvector|eigenvectors]] of $T$.

## Complex Spectral Theorem
**Statement**: Suppose $\mathbb{F} = \mathbb{C}$ and $T \in \mathcal{L}(V)$. Then the following are equivalent:
- $T$ is [[normal_operators|normal]].
- $T$ has a diagonal matrix with respect to some orthonormal basis of $V$.
- $V$ has an orthonormal basis consisting of eigenvectors of $T$.