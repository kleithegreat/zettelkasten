# Upper Triangular Matrices
The *diagonal* of a square [[matrices|matrix]] consists of the elements on the line from the upper left corner to the bottom right corner.
**Definition**: A square matrix is called *upper triangular* if all of its entries below the diagonal are zero.

Let $T \in \mathcal{L}(V)$ and $v_1, \ldots, v_n$ be a basis of $V$. The following are equivalent:
- The matrix of $T$ with respect to the basis $v_1, \ldots, v_n$ is upper triangular.
- $\text{span}(v_1, \ldots, v_k)$ is [[invariant_subspace|invariant]] under $T$ for all $k = 1, \ldots, n$.
- $Tv_k \in \text{span}(v_1, \ldots, v_k)$ for all $k = 1, \ldots, n$.

The [[eigenvalue|eigenvalues]] of an upper triangular matrix are the entries on the diagonal.

An operator $T$ on a finite-dimensional vector space $V$ has an upper-triangular matrix with respect to some basis of $V$ if and only if the [[minimal_polynomial|minimal polynomial]] of $T$ equals $(z - \lambda_1) \cdots (z - \lambda_m)$ for some $\lambda_1, \ldots, \lambda_m \in \mathbb{F}$.

Every operator on a finite-dimensional vector space over $\mathbb{C}$ has an upper-triangular matrix with respect to some basis of $V$.