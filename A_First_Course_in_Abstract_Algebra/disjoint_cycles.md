# Disjoint Cycles
Disjoint cycle notation allows us to represent [[set_permutation|permutations]] using each number only once.
For example, $$\sigma = \begin{pmatrix} 1 & 2 & 3 & 4 & 5 & 6 \\ 3 & 4 & 6 & 2 & 5 & 1 \end{pmatrix}$$ can be expressed as the product of disjoint cycles:
$$\sigma = (1, 3, 6)(2, 4).$$
This means that 1 goes to 3, 3 goes to 6, and 6 goes back to 1, while 2 goes to 4 and 4 goes back to 2. The cycle (5) is omitted since it is a fixed point.

We call these *cycles* because repeated applications of the permutation will cycle through the elements in the cycle.

A cycle containing $k$ elements is called a $k$-cycle and is an element of the $k$th [[symmetric_group|symmetric group]].

A 2-cycle is called a *transposition*.

Any cycle of length $n$ can be written as a product of $n-1$ transpositions.