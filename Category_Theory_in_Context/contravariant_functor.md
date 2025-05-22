# Contravariant Functor
**Definition**: A *contravariant [[functor]]* $F$ from $\mathsf{C}$ to $\mathsf{D}$ is a functor $F: \mathsf{C}^{op} \to \mathsf{D}$.
Explicitly, this consists of the following data:
- An object $Fc \in \mathsf{D}$ for each object $c \in \mathsf{C}$.
- A morphism $Ff: Fc' \to Fc$ in $\mathsf{D}$ for each morphism $f: c \to c'$ in $\mathsf{C}$.
These assignments are required to satisfy the following two functoriality axioms:
- For any composable pair $f, g$ in $\mathsf{C}$, $F(g \cdot f) = Ff \cdot Fg$.
- For each object $c \in \mathsf{C}$, $F(1_c) = 1_{Fc}$.