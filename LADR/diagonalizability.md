# Diagonal Matrices
**Definition**: A *diagonal matrix* is a square [[matrices|matrix]] that is zero everywhere except for possibly the diagonal.

An $M$ by $N$ matrix $A$ is diagonal if all entries are zero except for $a_{ii}$ for $i = 1, \ldots, \min(M, N)$.

An operator is *diagonalizable* if it has a diagonal matrix representation in some [[basis]].

Let $V$ be finite dimensional and $T \in \mathcal{L}(V)$ with [[eigenvalue|eigenvalues]] $\lambda_1, \ldots, \lambda_m$. The following are equivalent:
- $T$ is diagonalizable
- $V$ has a basis of [[eigenvector|eigenvectors]] of $T$
- $V = E(\lambda_1, T) \oplus \cdots \oplus E(\lambda_m, T)$
- $\dim V = \dim E(\lambda_1, T) + \cdots + \dim E(\lambda_m, T)$

If $V$ is finite dimensional and $T \in \mathcal{L}(V)$ has $\dim V$ distinct eigenvalues, then $T$ is diagonalizable.

If $V$ is finite dimensional and $T \in \mathcal{L}(V)$, $T$ is diagonalizable if and only if the [[minimal_polynomial|minimal polynomial]] of $T$ equals $(z - \lambda_1) \cdots (z - \lambda_m)$ for some list of distinct numbers $\lambda_1, \ldots, \lambda_m \in \mathbb{F}$.

If $T \in \mathcal{L}(V)$ is diagonalizable and $U$ is a subspace [[invariant_subspace|invariant]] under $T$, then $T|_U$ is diagonalizable over $U$.