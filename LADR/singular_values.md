# Singular Values
We use the following properties $T^*T$ for $T \in \mathcal{L}(V, W)$:
- $T^*T$ is a [[positive_operators|positive operator]] on $V$
- $\text{null}\; T^*T = \text{null}\; T$
- $\text{range}\; T^*T = \text{range}\; T^*$
- $\dim \text{range}\; T = \dim \text{range}\; T^*T = \dim \text{range}\; T^*$

**Definition**: Suppose $T \in \mathcal{L}(V, W)$. The *singular values* of $T$ are the nonnegative square roots of the eigenvalues of $T^*T$ in DESCENDING order, each included as many times as the dimension of the corresponding eigenspace of $T^*T$.

For $T \in \mathcal{L}(V, W)$, the following are true:
- $T$ is injective $\iff$ 0 is not a singular value of $T$
- the number of positive singular values of $T$ equals $\dim \text{range}\; T$
- $T$ is surjective $\iff$ number of positive singular values of $T$ equals $\dim W$

Comparison between singular values and eigenvalues:

| Eigenvalues | Singular values |
|-------------|-----------------|
| vector spaces | inner product spaces |
| operators | any linear map |
| arbitrary real or complex numbers | nonnegative numbers |
| can be empty list if $\mathbb{F} = \mathbb{R}$ | length of list is the dimension of the domain |
| includes 0 $\iff$ not invertible | includes 0 $\iff$ not injective |
| no standard order | descending order |