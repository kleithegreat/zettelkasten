# Gram-Schmidt Procedure
**Statement**: Suppose $v_1, \ldots, v_m$ is a linearly independent list of vectors in $V$. Let $f_1 = v_1$. For $k = 2, \ldots, m$, define $f_k$ inductively by
$$ f_k = v_k - \frac{\langle v_k, f_1 \rangle}{\|f_1 \|^2} f_1 - \cdots - \frac{\langle v_k, f_{k-1} \rangle}{\|f_{k-1}\|^2} f_{k-1}. $$
For each $k = 1, \ldots, m$, let $e_k = \frac{f_k}{\|f_k\|}$. Then $e_1, \ldots, e_m$ is an [[orthonormal_bases|orthonormal basis]] such that
$$\text{span}(v_1, \ldots, v_m) = \text{span}(e_1, \ldots, e_m)$$
for each $k = 1, \ldots, m$.

Important: Gram-Schmidt preserves [[span|spans]]!

Every finite-dimensional [[inner_products|inner product space]] has an orthonormal basis.