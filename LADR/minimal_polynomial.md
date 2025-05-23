# The Minimal Polynomial
A *monic* [[polynomials|polynomial]] is defined to have its highest degree coefficient equal to 1.

Existence, uniqueness, and degree of the minimal polynomial: let $V$ be a finite-dimensional [[vector_space|vector space]] and $T \in \mathcal{L}(V)$. Then there is a unique monic polynomial $p \in \mathcal{P}(F)$ of least degree such that $p(T) = 0$. Furthermore, $\text{deg}\;p \leq \dim V$.

**Definition**: Let $V$ be a finite dimensional vector space and $T \in \mathcal{L}(V)$. The *minimal polynomial* of $T$ is the unique monic polynomial $p \in \mathcal{P}(F)$ of least degree such that $p(T) = 0$.

To find the minimal polynomial of $T$, we can use the following steps:
- Pick $v \in V$ with $v \neq 0$.
- Consider $c_0 v + c_1 Tv + \cdots + c_{\dim V - 1} T^{\dim V - 1} v = -T^{\dim V} v$.
- Use a [[basis]] of $V$ to convert the equation into a system of $\dim V$ equations in $\dim V$ variables (the coefficients $c_i$).
- If we can find a solution, then $c_0, \ldots, c_{\dim V - 1}, 1$ are the coefficients of the minimal polynomial of $T$.

If $V$ is a finite-dimensional [[complex_numbers|complex]] vector space, then the minimal polynomial of $T$ has the form $(z - \lambda_1) \cdots (z - \lambda_m)$, where $\lambda_1, \ldots, \lambda_m$ are the distinct [[eigenvalue|eigenvalues]] of $T$ possibly with repetitions.

If $q(T) = 0$, then $q$ is a multiple of the minimal polynomial of $T$.

If $U$ is an [[invariant_subspace|invariant subspace]] of $V$ under $T$, then the minimal polynomial of $T$ is a multiple of the minimal polynomial of $T|_U$.

If $V$ is a finite-dimensional vector space over $\mathbb{R}$, $T \in \mathcal{L}(V)$, and $b, c \in \mathbb{R}$ where $b^2 < 4c$, then $\text{nullity}\; (T^2 - bT + cI)$ is even.

An operator $T$ is not [[invertibility|invertible]] if and only if the constant term of the minimal polynomial of $T$ is zero.