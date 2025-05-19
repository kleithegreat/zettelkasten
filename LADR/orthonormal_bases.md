# Orthonormal Bases
A list of vectors is called *orthonormal* if each vector has norm 1 and is orthogonal to all the other vectors in the list.

Alternatively, a list $e_1, \ldots, e_m$ of vectors is orthonormal if
$$ \langle e_i, e_j \rangle = \delta_{ij} $$

Bessel's Inequality: For an orthonormal list of vectors $e_1, \ldots, e_m$ in an [[inner_products|inner product]] space $V$, and any vector $v \in V$, we have
$$ |\langle v, e_1 \rangle|^2 + \ldots + |\langle v, e_m \rangle|^2 \leq ||v||^2 $$

**Definition**: An *orthonormal basis* is an orthonormal list that is also a [[basis]].

Every orthonormal list of length $\dim V$ is a basis for $V$.

There are a few ways to write a vector as a linear combination of an orthonormal basis:
- $v = \langle v, e_1 \rangle e_1 + \ldots + \langle v, e_m \rangle e_m$
- $\|v\|^2 = |\langle v, e_1 \rangle|^2 + \ldots + |\langle v, e_m \rangle|^2$
- $\langle u, v \rangle = \langle u, e_1 \rangle \overline{\langle v, e_1 \rangle} + \ldots + \langle u, e_m \rangle \overline{\langle v, e_m \rangle}$

Every orthonormal list extends to an orthonormal basis.

**Theorem** (Schur's Theorem): Every operator on a finite-dimensional complex inner product space has an upper triangular matrix with respect to some orthonormal basis.