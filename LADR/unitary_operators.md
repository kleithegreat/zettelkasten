# Unitary Operators
**Definition**: An operator $S \in \mathcal{L}(V)$ is called *unitary* if $S$ is an [[invertibility|invertible]] [[isometries|isometry]].

Suppose $S \in \mathcal{L}(V)$ is a unitary operator and $e_1, \ldots, e_n$ is an [[orthonormal_bases|orthonormal basis]] of $V$. Then the following are equivalent:
- $S^*S = I$
- $S$ is invertible and $S^{-1} = S^*$
- $Se_1, \ldots, Se_n$ is an orthonormal basis of $V$
- The rows of the [[matrices|matrix]] of $S$ with respect to the basis $e_1, \ldots, e_n$ form an orthonormal basis of $\mathbb{F}^n$ with respect to the Euclidean [[inner_products|inner product]]
- $S^*$ is a unitary operator

[[eigenvalue|Eigenvalues]] of unitary operators have absolute value 1 (NOTE: converse is NOT true).

If $\mathbb{F} = \mathbb{C}$ and $S \in \mathcal{L}(V)$, the following are equivalent:
- $S$ is unitary
- There is an orthonormal basis of $V$ consisting of [[eigenvector|eigenvectors]] of $S$ whose corresponding [[eigenvalue|eigenvalues]] all have absolute value 1

An $n \times n$ [[matrices|matrix]] is *unitary* if its columns form an orthonormal list in $\mathbb{F}^n$

Let $Q$ be an $n \times n$ matrix, then the following are equivalent:
- $Q$ is unitary
- The rows of $Q$ form an orthonormal list in $\mathbb{F}^n$
- $\|Qv\| = \|v\|$ for all $v \in \mathbb{F}^n$
- $Q^*Q = QQ^* = I$