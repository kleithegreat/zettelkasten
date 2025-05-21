# Category
**Definition**: A *category* consists of:
- A collection of *objects* $X, Y, Z, \ldots$
- A collection of *morphisms* (or *arrows*) between these objects $f, g, h, \ldots$
so that:
- Each morphism has a specified *domain* and *codomain* object.
- Each object has an *identity morphism* $1_X: X \to X$.
- For any pair of morphisms $f: X \to Y$ and $g: Y \to Z$, there is a *composition* morphism $g \circ f: X \to Z$.
subject to the following properties:
- For any $f: X \to Y$, $1_Y \circ f = f = f \circ 1_X$.
- Morphism composition is associative: $(h \circ g) \circ f = h \circ (g \circ f)$.