# Inner Products
**Definition**: An *inner product* on $V$ is a function that takes each ordered pair $(u,v)$ of vectors in $V$ to a number $\langle u,v \rangle \in \mathbb{F}$ and has the following properties:
- Positive definiteness: $\langle u, u \rangle \geq 0$ and $\langle u, u \rangle = 0$ if and only if $u = 0$
- Linearity in the first argument: $\langle u + v, w \rangle = \langle u, w \rangle + \langle v, w \rangle$ and $\langle cu, v \rangle = c\langle u, v \rangle$ for all $c \in \mathbb{F}$
- Conjugate symmetry: $\langle u, v \rangle = \overline{\langle v, u \rangle}$

Basic properties of inner products:
- $\langle 0, v \rangle = 0$ and $\langle v, 0 \rangle = 0$ for all $v \in V$
- $\langle u, v + w \rangle = \langle u, v \rangle + \langle u, w \rangle$ for all $u, v, w \in V$
- $\langle u, \lambda v \rangle = \overline{\lambda} \langle u, v \rangle$ for all $u, v \in V$ and $\lambda \in \mathbb{F}$

Two vectors are *orthogonal* if $\langle u, v \rangle = 0$.
- 0 is orthogonal to every vector.
- 0 is the only vector orthogonal to itself.

If $V$ is a [[complex_numbers|COMPLEX]] inner product space and $T \in \mathcal{L}(V)$, then $$ \langle Tv, v \rangle = 0 \; \text{for every} \; v \in V \iff T = 0 $$