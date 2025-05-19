# Isometries
**Definition**: A linear map $S \in \mathcal{L}(V, W)$ is called an *isometry* if
$$ \|Sv\| = \|v\| $$
for every $v \in V$. In other words, a linear map is an isometry if it preserves [[norms]].

Suppose $S \in \mathcal{L}(V, W)$ is an isometry, $e_1, \ldots, e_n$ is an [[orthonormal_bases|orthonormal basis]] of $V$, and $f_1, \ldots, f_m$ is an orthonormal basis of $W$. Then the following are equivalent:
- $S^*S = I$
- $\langle Su, Sv \rangle = \langle u, v \rangle$ for all $u, v \in V$
- $Se_1, \ldots, Se_n$ is an orthonormal list in $W$
- The columns of the matrix of $S$ with respect to the bases of $V$ and $W$ form an orthonormal list in $\mathbb{F}^m$ with respect to the Euclidean [[inner_products|inner product]]

Every isometry is injective.

Let $S \in \mathcal{L}(V, W)$. Then $S$ is an isometry if and only if all [[singular_values|singular values]] of $S$ are 1.