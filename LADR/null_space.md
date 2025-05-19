# Null Space
**Definition**: For $T \in \mathcal{L}(V, W)$, the *null space* of $T$ is the [[subspaces|subspace]] of $V$ that gets mapped to the zero vector in $W$.

A [[linear_map|linear map]] $T$ is injective if and only if its null space is trivial.

Null spaces of powers of $T$:

Suppose $T \in \mathcal{L}(V)$. Then
$$ \{0\} = \text{null}\;T^0 \subseteq \text{null}\;T^1 \subseteq \cdots \subseteq \text{null}\;T^k \subseteq \text{null}\;T^{k+1} \subseteq \cdots $$

Suppose $T \in \mathcal{L}(V)$ and $m$ is a nonnegative integer such that $\text{null}\;T^m = \text{null}\;T^{m+1}$. Then
$$ \text{null}\;T^m = \text{null}\;T^{m+1} = \text{null}\;T^{m+2} = \cdots $$

Suppose $T \in \mathcal{L}(V)$. Then
$$ \text{null}\;T^{\dim V} = \text{null}\;T^{\dim V + 1} = \text{null}\;T^{\dim V + 2} = \cdots $$

$V$ is the [[direct_sum|direct sum]] of of $\text{null}\;T^{\dim V}$ and $\text{range}\;T^{\dim V}$.
Suppose $T \in \mathcal{L}(V)$. Then
$$ V = \text{null}\;T^{\dim V} \oplus \text{range}\;T^{\dim V}. $$