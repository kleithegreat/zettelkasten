# Eigenvalues
**Definition**: Let $T \in \mathcal{L}(V)$. A scalar $\lambda \in \mathbb{F}$ is an **eigenvalue** of $T$ if there exists a nonzero vector $v \in V$ such that $T(v) = \lambda v$.

Equivalent conditions to be an eigenvalue (for finite-dimensional $V$, $T \in \mathcal{L}(V)$ and $\lambda \in \mathbb{F}$):
- $\lambda$ is an eigenvalue of $T$
- $T - \lambda I$ is not injective
- $T - \lambda I$ is not surjective
- $T - \lambda I$ is not invertible

Every operator on a finite-dimensional nonzero complex vector space has at least one eigenvalue. Related: [[fundamental_theorem_algebra|Fundamental Theorem of Algebra]].

Eigenvalues are the zeros of the [[minimal_polynomial|minimal polynomial]].

Every operator on an odd-dimensional vector space (real included) has at least one eigenvalue.

Properties of an operator determined by its eigenvalues:

| property | eigenvalues contained in |
| --- | --- |
| invertible | $\mathbb{C} \setminus \{0\}$ |
| self-adjoint | $\mathbb{R}$ |
| skew ($A^T = -A$) | $\{\lambda \in \mathbb{C} : \text{Re}\; \lambda = 0 \}$ |
| orthogonal proejction | $\{0, 1\}$ |
| positive | $[0, \infty)$ |
| unitary | $\{\lambda \in \mathbb{C} : \text{abs}(\lambda) = 1 \}$ |
| norm is less than 1 | $\{\lambda \in \mathbb{C} : \text{abs}(\lambda) < 1 \}$ |