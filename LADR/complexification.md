# Complexification
**Definition**: Suppose $V$ is an $\mathbb{R}$-[[vector_space|vector space]]. The *complexification* of $V$, denoted $V_\mathbb{C}$ equals $V \times V$. An element in $V_\mathbb{C}$ is a pair $(u, v)$ where $u, v \in V$, but we write it $u + iv$.

Vector addition is defined componentwise:
$$ (u_1 + iv_1) + (u_2 + iv_2) = (u_1 + u_2) + i(v_1 + v_2) $$

Complex scalar multiplication is defined as:
$$ (a + ib)(u + iv) = (au - bv) + i(au + bv) $$
where $a, b \in \mathbb{R}$ and $u, v \in V$.

If $V$ is an $\mathbb{R}$-vector space, then $V_\mathbb{C}$ is a $\mathbb{C}$-vector space.

If $V$ is an $\mathbb{R}$-vector space, then:
- If $v_1, \ldots, v_n$ is a basis for $V$ as an $\mathbb{R}$-vector space, then $v_1, \ldots, v_n$ is a basis for $V_\mathbb{C}$ as a $\mathbb{C}$-vector space.
- $\dim_\mathbb{R} V = \dim_\mathbb{C} V_\mathbb{C}$.

Suppose $V$ is an $\mathbb{R}$-vector space and $T \in \mathcal{L}(V)$. The *complexification of T* denoted $T_\mathbb{C}$ is the operator $T_\mathbb{C} \in \mathcal{L}(V_\mathbb{C})$ defined by:
$$ T_\mathbb{C}(u + iv) = T(u) + iT(v) $$
for $u, v \in V$.

The [[matrices|matrix]] of an operator with respect to some basis is equal to the matrix of the complexification of that operator with respect to the complexification of that [[basis]].

If $\lambda \in \mathbb{C}$ is an [[eigenvalue]] of $T_\mathbb{C}$ and $u + iv$ is a corresponding [[eigenvector]], then $u - iv$ is an eigenvector of $T_\mathbb{C}$ with eigenvalue $\overline{\lambda}$.

If $V$ is an $\mathbb{R}$-vector space and $T \in \mathcal{L}(V)$, then:
- $\lambda \in \mathbb{R}$ is an eigenvalue of $T_\mathbb{C} \iff \lambda$ is an eigenvalue of $T$.
- If $\lambda \in \mathbb{C}$ is an eigenvalue of $T_\mathbb{C}$, then $\overline{\lambda}$ is also an eigenvalue of $T_\mathbb{C}$ with the same algebraic [[multiplicity]].

The [[characteristic_polynomial|characteristic polynomial]] of $T_\mathbb{C}$ has real coefficients.

The [[minimal_polynomial|minimal polynomial]] $q$ of $T_\mathbb{C}$ has real coefficients and $q(T) = 0$.

We can find the minimal polynomial of $T$ by complexifying it and computing over $\mathbb{C}$. Then the outcome has real coefficients and is the minimal polynomial of $T$.