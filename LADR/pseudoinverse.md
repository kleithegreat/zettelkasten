# Pseudoinverse
Suppose $V$ is finite-dimensional and $T \in \mathcal{L}(V, W)$. Then $T|_{(\text{null}\; T)^\perp}$ is an [[isomorphism]] between $(\text{null}\; T)^\perp$ and $\text{range}\; T$.

**Definition**: Suppose that $V$ is finite-dimensional and $T \in \mathcal{L}(V, W)$. The **pseudoinverse** $T^\dagger \in \mathcal{L}(W, V)$ of $T$ is the linear map from $W$ to $V$ defined by
$$ T^\dagger w = (T_{(\text{null}\; T)^\perp})^{-1} P_{\text{range}\; T} w $$
for each $w \in W$.

Algebraic properties of the pseudoinverse:
Assuming $V$ is finite dimensional and $T \in \mathcal{L}(V, W)$,
- If $T$ is invertible, then $T^\dagger = T^{-1}$.
- $TT^\dagger = P_{\text{range}\; T}$.
- $T^\dagger T = P_{(\text{null}\; T)^\perp}$.

The pseudoinverse provides a best approximation to the solution of the equation $T v = w$.
Suppose $V$ is finite-dimensional, $T \in \mathcal{L}(V, W)$, and $w \in W$.
- If $v \in V$, then $\|T(T^\dagger w) - w\| \leq \|Tv - w\|$ with equality if and only if $v \in T^\dagger w + \text{null}\; T$.
- If $v \in T^\dagger w + \text{null}\; T$, then $\|T^\dagger w\| \leq \|v\|$ with equality if and only if $v = T^\dagger w$.