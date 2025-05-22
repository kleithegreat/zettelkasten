# Natural Transformation
**Definition**: Given categories $\mathsf{C}$ and $\mathsf{D}$ and [[functor|functors]] $F, G: \mathsf{C} \to \mathsf{D}$, a *natural transformation* $\alpha: F \Rightarrow G$ consists of:
- a morphism $\alpha_c: Fc \to Gc$ in $\mathsf{D}$ for each object $c$ in $\mathsf{C}$ called the *component* of $\alpha$ at $c$,
so that for any morphism $f: c \to c'$ in $\mathsf{C}$, the following square of morphisms in $\mathsf{D}$:
```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd}
Fx && Gx \\
      \\
      Fy && Gy
      \arrow["{\alpha_x}", from=1-1, to=1-3]
      \arrow["Ff"', from=1-1, to=3-1]
      \arrow["Gf", from=1-3, to=3-3]
      \arrow["{\alpha_y}", from=3-1, to=3-3]
\end{tikzcd}
\end{document}
```
commutes, i.e., has a common composite $Fc \to Gc'$ in $\mathsf{D}$. Alternatively, $Gf \circ \alpha_c = \alpha_{c'} \circ Ff$.