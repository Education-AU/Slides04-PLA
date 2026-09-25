---
title: Linear Continuation
template: default
---
Linear maps are fixed by their values on a basis. That is, if we know the values of a linear map on a basis, we can determine the value of the map on any vector in the domain.

Consider finite dimensional vectorspaces $V$ and $W$ with some basis for $V$
$$
\begin{aligned}
\{ \mathbf{e}_1,\mathbf{e}_2,\dots ,\mathbf{e}_n \} \subset V
\end{aligned}
$$
Let's say we know the images of the basis vectors mapped by $L$
$$
L:V \to W , L(\mathbf{e}_i)=\mathbf{w}_i
$$
where $\mathbf{w}_i\in W$ are images of the basis in $W$

Then we can calculate the image of any vector $\mathbf{v}\in V$ by first expressing it in terms of the basis vectors

Let $\mathbf{v}\in V$.

$$
L(\mathbf{v})=  L\left(\sum_{i=1}^n c_i\mathbf{e}_i\right)=\sum_{i=1}^n c_iL(\mathbf{e}_i) = \sum_{i=1}^n c_i\mathbf{w}_i
$$
