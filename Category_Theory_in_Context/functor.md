# Functor
**Definition**: A *functor* $F: \mathsf{C} \to \mathsf{D}$, between [[category|categories]] $\mathsf{C}$ and $\mathsf{D}$, consists of the following data:
- An object $Fc \in \mathsf{D}$ for each object $c \in \mathsf{C}$.
- A morphism $Ff: Fc \to Fc' \in \mathsf{D}$ for each morphism $f: c \to c'$ in $\mathsf{C}$.
These assignments are required to satisfy the following two functoriality axioms:
- For any composable pair $f, g$ in $\mathsf{C}$, $Fg \cdot Ff = F(g \cdot f)$.
- For each object $c \in \mathsf{C}$, $F(1_c) = 1_{Fc}$.