# Singular Value Decomposition
**Statement**: Suppose $T \in \mathcal{L}(V, W)$, and the positive singular values of $T$ are $s_1, \ldots, s_m$. Then there exist orthonormal lists $e_1, \ldots, e_m$ in $V$ and $f_1, \ldots, f_m$ in $W$ such that
$$ Tv = s_1 \langle v, e_1 \rangle f_1 + \cdots + s_m \langle v, e_m \rangle f_m $$
for every $v \in V$.

SVD of adjoint and pseudoinverse:
Suppose $T \in \mathcal{L}(V, W)$, and the positive singular values of $T$ are $s_1, \ldots, s_m$. Suppose $e_1, \ldots, e_m$ and $f_1, \ldots, f_m$ are orthonormal lists in $V$ and $W$, respectively, such that
$$ Tv = s_1 \langle v, e_1 \rangle f_1 + \cdots + s_m \langle v, e_m \rangle f_m $$
for every $v \in V$. Then the adjoint $T^* \in \mathcal{L}(W, V)$ has the singular value decomposition
$$ T^*w = s_1 \langle w, f_1 \rangle e_1 + \cdots + s_m \langle w, f_m \rangle e_m $$
and the pseudoinverse $T^\dagger \in \mathcal{L}(W, V)$ has the singular value decomposition
$$ T^\dagger w = \frac{\langle w, f_1 \rangle}{s_1} e_1 + \cdots + \frac{\langle w, f_m \rangle}{s_m} e_m $$
for every $w \in W$.

Matrix version of SVD:
Suppose $A$ is a $p$ by $n$ matrix of rank $m \geq 1$. Then there exist a $p$ by $m$ matrix $B$ with orthonormal columns, an $m$ by $m$ diagonal matrix $D$ with positive entries, and and $n$ by $m$ matrix $C$ with orthonormal columns such that
$$ A = BDC^*. $$
