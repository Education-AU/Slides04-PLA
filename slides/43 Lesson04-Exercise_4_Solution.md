---
title: Exercise 4 solution
template: default
---

Since the domain and co-domain are the same vectorspace space we have by the change of basis formula that,
$$
d'=P_{e'\rightarrow e}^{-1}AP_{e'\rightarrow e}c'
$$
We choose this version, since basis change to the standard basis the most convenient

Doing this in numpy we have the following code:

#### solution code

``` python runnable solution code
import numpy as np
A = np.array([[2, 1], [1, 2]])
b_1=np.array([1, 1])
b_2=np.array([1, -1])
P=np.column_stack((b_1, b_2))

A_new=np.linalg.inv(P)@A@P

print(A_new)

```