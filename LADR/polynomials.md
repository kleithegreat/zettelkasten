# Polynomials
**Definition**: A function $p: \mathbb{F} \to \mathbb{F}$ is a *polynomial* with coefficients in $\mathbb{F}$ if there exists a list of scalars $a_0, \ldots, a_n$ such that
$$ p(z) = a_0 + a_1 z + \ldots + a_n z^n $$
for all $z \in \mathbb{F}$.

We denote $\mathcal{P}(F)$ as the set of all polynomials with coefficients in $\mathbb{F}$.

The **degree** of a polynomial is the highest power of $z$ that appears in the polynomial. The degree of the zero polynomial is defined to be $-\infty$.

We denote $\mathcal{P}_m(\mathbb{F})$ as the set of all polynomials with degree at most $m$.

A number $\lambda \in \mathbb{F}$ is a *root* of a polynomial $p \in \mathcal{P}(\mathbb{F})$ if $p(\lambda) = 0$.

Each zero of a polynomial corresponds to a linear factor of the polynomial. In other words, $p(\lambda) = 0$ if and only if $p(z) = (z - \lambda)q(z)$ for some polynomial $q(z)$. Related: [[polynomial_division_algorithm|Division Algorithm for Polynomials]].

A polynomial of degree $m$ has at most $m$ roots in $\mathbb{F}$. Related: [[fundamental_theorem_algebra|Fundamental Theorem of Algebra]].

For $p \in \mathcal{P}(\mathbb{C})$, with real coefficients, the roots of $p$ come in complex conjugate pairs.

Let $b, c \in \mathbb{R}$. The polynomial $x^2 + bx + c$ can be factored as $(x - \lambda_1)(x - \lambda_2)$ if and only if $b^2 \geq 4c$.

Suppose $p \in \mathcal{P}(\mathbb{R})$ is a nonconstant polynomial. Then $p$ has a unique factorization (except for the order of the factors) of the form $$ p(x) = c(x - \lambda_1) \cdots (x - \lambda_m) (x^2 + b_1 x + c_1) \cdots (x^2 + b_k x + c_k) $$
where $c, \lambda_1, \ldots, \lambda_m, b_1, \ldots, b_k, c_1, \ldots, c_k \in \mathbb{R}$, with $b_i^2 < 4c_i$ for $i = 1, \ldots, k$.