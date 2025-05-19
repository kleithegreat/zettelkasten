# Generalized Eigenspaces
**Definition**: Suppose $T \in \mathcal{L}(V)$ and $\lambda \in \mathbb{F}$. The *generalized eigenspace* of $T$ corresponding to $\lambda$, denoted $G(\lambda, T)$, is defined by
$$ G(\lambda, T) =  \{v \in V : (T - \lambda I)^k v = 0 \text{ for some positive integer } k\}. $$
Thus $G(\lambda, T)$ is the set of [[generalized_eigenvectors|generalized eigenvectors]] of $T$ corresponding to $\lambda$ with the 0 vector.

Description of generalized eigenspaces: $G(\lambda, T) = \text{null}\;(T - \lambda I)^{\dim V}$

Generalized eigenspace decomposition:
Suppose $\mathbb{F} = \mathbb{C}$ and $T \in \mathcal{L}(V)$. Let $\lambda_1, \ldots, \lambda_m$ be the distinct eigenvalues of $T$. Then
- $G(\lambda_k, T)$ is invariant under $T$ for each $k = 1, \ldots, m$.
- $(T - \lambda_k I)_{G(\lambda_k, T)}$ is nilpotent for each $k = 1, \ldots, m$.
- $V = G(\lambda_1, T) \oplus \cdots \oplus G(\lambda_m, T)$.