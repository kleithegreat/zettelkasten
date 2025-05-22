# Hom Functor
**Definition**: If $\mathsf{C}$ is a [[locally_small_category|locally small category]], then for any object $c \in \mathsf{C}$, we can define a pair of covariant and [[contravariant_functor|contravariant]] functors, called the *hom functor*.

The covariant hom functor $\mathsf{C}(c, -)$ is defined as follows:
- $x \mapsto \mathsf{C}(c, x)$ for each object $x \in \mathsf{C}$.
- $f: x \to y \mapsto f_*: \mathsf{C}(c, x) \to \mathsf{C}(c, y)$ for each morphism $f: x \to y$ in $\mathsf{C}$.

The contravariant hom functor $\mathsf{C}(-, c)$ is defined as follows:
- $x \mapsto \mathsf{C}(x, c)$ for each object $x \in \mathsf{C}$.
- $f: x \to y \mapsto f^*: \mathsf{C}(y, c) \to \mathsf{C}(x, c)$ for each morphism $f: x \to y$ in $\mathsf{C}$.


There is also a *two-sided* hom functor $\mathsf{C}(-, -): \mathsf{C}^{op} \times \mathsf{C} \to \mathbf{Set}$, which is defined as follows:
- $(x, y) \mapsto \mathsf{C}(x, y)$ for each pair of objects $x, y \in \mathsf{C}$.
- $(f, h) \mapsto (f^*, h_*): \mathsf{C}(x, y) \to \mathsf{C}(w, z)$ for each pair of morphisms $f: w \to x$ and $h: y \to z$ in $\mathsf{C}$.