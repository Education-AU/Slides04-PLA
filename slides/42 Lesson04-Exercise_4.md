---
title: Exercise 4 Change of basis
template: default
---

Let $T:\mathbb R^2\to\mathbb R^2$ be defined in the standard basis by a matrix

$$
A=\begin{pmatrix}2&1\\1&2\end{pmatrix}.
$$

Consider the basis $\mathcal B=\{ (1,1), (1,-1)\}$ of $\mathbb R^2$.

Find the matrix representing $T$ in the basis $\mathcal B$.

Since the domain and codomain are the same vectorspace space we have by the change of basis formula that,
$$
d'=P_{e'\rightarrow e}^{-1}AP_{e'\rightarrow e}c'
$$
We choose this version, since basis change to the standard basis the simplest

Doing this in numpy we have the following code:

``` python runnable exercise code
import numpy as np
A = np.array([[2, 1], [1, 2]])
b_1=np.array([1, 1])
b_2=np.array([1, -1])

P=0# correct

A_new=0# correct

print(A_new)

```