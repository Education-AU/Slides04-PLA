---
title: Exercise 3 Solution
template: two-column
---

#### Solution a

$$
A=\begin{pmatrix}1&2\\0&1\end{pmatrix},
\qquad
B=\begin{pmatrix}2&0\\1&1\end{pmatrix}.
$$

1. Find the matrices representing $S\circ T$ and $T\circ S$, assuming $A$ represents $S$ and $B$ represents $T$.
2. Are the two compositions equal?



``` python runnable Solution a
import numpy as np
A=np.array([[1, 2], [0, 1]])
B=np.array([[2, 0], [1, 1]])
AB=A@B
BA=B@A
print(AB)
print(BA)
``` 

<!-- column -->

#### Solution b

Let $T:\mathbb R^2\to\mathbb R^2$ be determined by matrix in standard basis of $\mathbb R^2$ as
$$
A=\begin{pmatrix}2&1\\4&2\end{pmatrix}
$$
Determine whether $T$ is invertible by calculating determinant. If it is not, find a nonzero vector mapped to zero.

``` python runnable Solution b
import numpy as np
A=np.array([[2, 1], [4, 2]])
det_A=np.linalg.det(A)
print(det_A)
```     

To find the null space, we can solve the equation $Ax=0$ for a nonzero vector $x$.
Which you can easily show could be $(1,-2)$

