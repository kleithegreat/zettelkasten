# Trace
**Definition**: Suppose $A$ is a square matrix with entries in $\mathbb{F}$. The *trace* of $A$, denoted by $\text{tr}\;A$, is defined to be the sum of the diagonal entries of $A$.

The trace of $AB$ is equal to the trace of $BA$

Trace does not depend on the choice of [[basis]].

The trace of an operator is the trace of its [[matrices|matrix]] representation with respect to any basis.

On complex vector spaces, the trace of an operator is equal to the sum of its [[eigenvalue|eigenvalues]], with each eigenvalue counted with its algebraic [[multiplicity]].

On complex vector spaces, $\text{tr}\;T$ equals the negative of the coefficient of $z^{\dim V - 1}$ in the [[characteristic_polynomial|characteristic polynomial]] of $T$.

If $V$ is an [[inner_products|inner product space]] with an orthonormal basis $e_1, \ldots, e_n$, then $\text{tr}\;T = \langle Te_1, e_1 \rangle + \cdots + \langle Te_n, e_n \rangle$.

Trace is a [[functionals|linear functional]] $\text{tr}: \mathcal{L}(V) \to \mathbb{F}$ such that $\text{tr}(ST) = \text{tr}(TS)$ for all $S, T \in \mathcal{L}(V)$.

There do not exist operators $S, T \in \mathcal{L}(V)$ such that $ST - TS = I$.