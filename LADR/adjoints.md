# Adjoints
**Definition**: Suppose $T \in \mathcal{L}(V, W)$. The *adjoint* of $T$ is the function $T^*: W \to V$ such that
$$ \langle Tv, w \rangle = \langle v, T^*w \rangle $$
for every $v \in V$ and $w \in W$.

The adjoint is linear and unique.

Basic properties of adjoints assuming $T \in \mathcal{L}(V, W)$:
- $(S + T)^* = S^* + T^*$
- $(cT)^* = \overline{c}T^*$ for $c \in \mathbb{C}$
- $(T^*)^* = T$
- $(ST)^* = T^*S^*$ for $S \in \mathcal{L}(W, U)$ where $U$ is a finite-dimensional [[inner_products|inner product]] space
- $I^* = I$
- If $T$ is [[invertibility|invertible]], then $T^*$ is also invertible and $(T^{-1})^* = (T^*)^{-1}$.

[[null_space|Null space]] and [[range]] of adjoints:
- $\text{null}(T^*) = \text{range}(T)^\perp$
- $\text{range}(T^*) = \text{null}(T)^\perp$
- $\text{null}(T) = \text{range}(T^*)^\perp$
- $\text{range}(T) = \text{null}(T^*)^\perp$

Related: [[orthogonal_complements|orthogonal complement]].

The adjoint of a [[matrices|matrix]] is its [[complex_numbers|conjugate]] transpose.