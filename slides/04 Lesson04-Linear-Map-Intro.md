---
title: Introduction to Linear Maps
template: default
---

So far, we have studied the structure of a vector space: vectors, linear combinations, bases, coordinates, and subspaces.

We now want to study **maps between vector spaces**.

A map
$$
L:V\to W
$$
assigns each vector in $V$ a vector in $W$. A general map can transform vectors in many different ways. Some maps preserve the structure of vector spaces, while others do not.

We will focus on **linear maps**, which preserve the two operations of vector spaces:

$L(\mathbf u+\mathbf v)=L(\mathbf u)+L(\mathbf v)$ and $L(c\mathbf v)=cL(\mathbf v)$.

Equivalently, a linear map preserves **linear combinations**:

$$
L(c_1\mathbf v_1+\cdots+c_k\mathbf v_k)
=
c_1L(\mathbf v_1)+\cdots+c_kL(\mathbf v_k).
$$

Maps that do not satisfy these properties are called **nonlinear maps**.

This property makes linear maps particularly useful. Since every vector can be written as a linear combination of basis vectors, the action of a linear map on an entire vector space is determined by its action on a basis.

This also gives a natural connection between linear maps, coordinates, and **matrices**.
