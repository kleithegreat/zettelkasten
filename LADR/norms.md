# Norms
**Definition**: For $v \in V$, the *norm* of $v$, denoted $\|v\|$, is defined by $$ \|v\| = \sqrt{\langle v, v \rangle}. $$

Related: [[inner_products|inner product]]

Basic properties of norms:
- $\|v\| = 0$ if and only if $v = 0$
- $\|cv\| = |c|\|v\|$ for all $c \in \mathbb{F}$

If $u$ and $v$ are orthogonal, then $\|u + v\|^2 = \|u\|^2 + \|v\|^2$.

Cauchy-Schwarz inequality: For all $u, v \in V$, $$ |\langle u, v \rangle| \leq \|u\|\|v\|. $$

Triangle inequality: For all $u, v \in V$, $$ \|u + v\| \leq \|u\| + \|v\|. $$

Parallelogram inequality: For all $u, v \in V$, $$ \|u + v\|^2 + \|u - v\|^2 = 2\|u\|^2 + 2\|v\|^2. $$

If $T \in \mathcal{L}(V, W)$ and $s_1$ is the largest [[singular_values|singular value]] of $T$, then $\|Tv\| \leq s_1\|v\|$ for all $v \in V$.

The norm of a linear map $T \in \mathcal{L}(V, W)$ is defined by $$ \|T\| = \max\{\|Tv\| : v \in V, \|v\| \leq 1\}$$

Basic properties of the norm of a linear map:
- $\|T\| \geq 0$ and $\|T\| = 0$ if and only if $T = 0$
- $\|cT\| = |c|\|T\|$ for all $c \in \mathbb{F}$
- $\|S + T\| \leq \|S\| + \|T\|$ for all $S, T \in \mathcal{L}(V, W)$

Alternative formulation of the norm of a linear map $T \in \mathcal{L}(V, W)$:
- The largest singular value of $T$
- $\max\{\|Tv\| : v \in V, \|v\| = 1\}$
- The smallest number $c$ such that $\|Tv\| \leq c\|v\|$ for all $v \in V$

For $T \in \mathcal{L}(V, W)$, $\|T\| = \|T^*\|$.