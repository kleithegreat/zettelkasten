# Dihedral Group
Let the points of $U_n$ be the vertices of a regular $n$-gon which we will denote as $P_n$. Label the points of $P_n$ as $0, 1, \ldots, n-1$ starting from $(1, 0)$ in the counterclockwise direction. If $n \geq 3$, then $D_n$ is the set of all bijections $\phi: \mathbb{Z}_n \to \mathbb{Z}_n$ such that vertices $i$ and $j$ are vertices of the same edge of $P_n$ if and only if $\phi(i)$ and $\phi(j)$ are vertices of the same edge of $P_n$.

The *nth dihedral group* is the set $D_n$ under composition.

The nth dihegral [[group]] describes the rotational and reflective symmetries of a regular $n$-gon, and has order $2n$.

Let $\iota$ be the [[identity]], $\rho$ be the rotation by $\frac{2\pi}{n}$, and $\mu$ be the reflection across the horizontal axis. Then the elements of $D_n$ are:
$$ \iota, \rho, \rho^2, \ldots, \rho^{n-1}, \mu, \mu\rho, \mu\rho^2, \ldots, \mu\rho^{n-1} $$