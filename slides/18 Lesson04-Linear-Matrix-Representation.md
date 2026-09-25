---
title: Matrix representation of a Linear map
template: default
---

What about the other way around? Does any matrix represent a linear map? The answer is yes, but we need to choose
**fixed bases** in the domain and codomain.

Consider finite dimensional vectorspaces $V,\lvert V \rvert =n$ and $W,\lvert W\rvert =m$. Also consider a
matrix $A$ with shape $m\times n$.

Now, consider **any** bases in $V$ and $W$

$$
\begin{aligned}
\{ \mathbf{e}_1,\mathbf{e}_2,\dots ,\mathbf{e}_n \},
\{ \mathbf{f}_1,\mathbf{f}_2,\dots ,\mathbf{f}_m \}
\end{aligned}
$$

And define the map $L_A:V \to W$ for any $\mathbf{v}\in V$

$$
L_A (\mathbf{v})=L_A (\sum_{j=1}^n c_j \mathbf{e} _j)=
\sum_{i=1}^m (\sum_{j=1}^n a_{ij}c_j)\mathbf{f} _i
$$
This can also be formulated in matrix language

$$
\begin{aligned}
d_i&=\sum_{j=1}^n a_{ij}c_j\\
d&=Ac
\end{aligned}
$$
This is obviously linear, and we have shown that any matrix represents a linear map, but we need to choose bases in the
domain and codomain. The matrix itself has no knowledge of the spaces it is mapping between, it is just a collection of
numbers. The bases are what give the matrix meaning as a linear map.

