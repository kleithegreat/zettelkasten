# Block Diagonal Matrices
**Definition**: A *block diagonal matrix* is a square [[matrices|matrix]] whose diagonal consists of square matrices and all other entries are zero.

Suppose $\mathbb{F} = \mathbb{C}$ and $T \in \mathcal{L}(V)$. Let $\lambda_1, \ldots, \lambda_m$ be the distinct [[eigenvalue|eigenvalues]] of $T$ with [[multiplicity|multiplicities]] $d_1, \ldots, d_m$. Then there is a [[basis]] of $V$ where the matrix of $T$ is of the form
$$ \begin{pmatrix} A_1 & & 0 \\ & \ddots & \\ 0 & & A_m \end{pmatrix} $$
where each $A_k$ is a $d_k$-by-$d_k$ [[upper_triangular_matrices|upper triangular]] matrix of the form
$$ A_k = \begin{pmatrix} \lambda_k & & * \\ & \ddots & \\ 0 & & \lambda_k \end{pmatrix}. $$