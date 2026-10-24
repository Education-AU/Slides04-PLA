---
title: Exercise 3 Composition of linear maps
template: two-column
---

#### Exercise a

Let $S,T:\mathbb R^2\to\mathbb R^2$ be defined by matrices in standard basis of $\mathbb R^2$ as

$$
A=\begin{pmatrix}1&2\\0&1\end{pmatrix},
\qquad
B=\begin{pmatrix}2&0\\1&1\end{pmatrix}.
$$

1. Find the matrices representing $S\circ T$ and $T\circ S$, assuming $A$ represents $S$ and $B$ represents $T$.
2. Are the two compositions equal?

You can use the following code to solve the exercise in Python:

``` python runnable Exercise a
import numpy as np
A=0 #correct
B=0 #correct
print("")#correct
print("")#correct
```     

<!-- column -->

## Exercise b

Let $T:\mathbb R^2\to\mathbb R^2$ be determined by matrix in standard basis of $\mathbb R^2$ as
$$
A=\begin{pmatrix}2&1\\4&2\end{pmatrix}
$$
Determine whether $T$ is invertible by calculating determinant. If it is not, find a nonzero vector mapped to zero.

``` python runnable Exercise b
import numpy as np
A=0 #correct
print("")# print determinant
```     
