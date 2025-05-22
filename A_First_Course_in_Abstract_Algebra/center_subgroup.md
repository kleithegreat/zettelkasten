# Center of a Group
**Definition** The *center* of a group $G$ $Z(G)$ is defined by
$$ Z(G) = \{z \in G \mid zg = gz \text{ for all } g \in G\} $$

The center is a [[normal_subgroup|normal subgroup]].

The *i-th center* of a group $G$ is defined inductively as:
- $Z_0(G) = \{e\}$
- $Z_{i+1}(G) = \pi_i^{-1}(Z(G/Z_i(G)))$ where $\pi_i: G \to G/Z_i(G)$ is the canonical projection.