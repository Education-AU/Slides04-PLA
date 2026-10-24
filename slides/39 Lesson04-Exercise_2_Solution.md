---
title: Exercise 2
template: two-column
---


$$
A=\begin{pmatrix}
1&2&1\\
2&4&1
\end{pmatrix}.
$$

#### 1

The map cannot be invertible because the dimension of domain is 3 and the dimension of the codomain is 2.

#### 2

To find kernel we solve the equation $Ax=0$.

$$
x+2y+z=0\\
2x+4y+z=0
$$
subtracting the first equation from the second we get
$$
x+2y=0
$$
Which is a line in the x-y plane. This is a one dimensional subspace of $\mathbb{R}^3$    
$$
c (1,2,0)
$$
That is the kernel of $A$ is spanned by the vector $(1,2,0)$ and has dimension 1.
<!-- column -->

#### 3

To find the image we can use the fact that the image is spanned by the columns of $A$. That is the image is spanned by
the vectors $(1,2)$, $(2,4)$ and $(1,1)$. Since the second vector is a multiple of the first and the third vector
linearly independent of the first we can conclude that the image is spanned by the vectors $(1,2)$ and $(1,1)$ and has
dimension 2.

This matches the rank-nullity theorem which states that the dimension of the kernel plus the dimension of the image
equals dimension of the domain.

$T$ cannot be injective since the kernel is not trivial. $T$ is surjective since the image is all of $\mathbb{R}^2$.