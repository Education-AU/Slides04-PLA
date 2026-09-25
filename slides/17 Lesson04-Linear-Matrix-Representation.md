---
title: Matrix representation of a Linear map
template: default
---

We can now read off the coordinates say $d_i$ in the codomain basis
$$
d_i=\sum_{j=1}^n a_{ij}c_j, i=1..m
$$
This is in fact our matrix equation $d=Ac$ where the matrix $j$-column is the coefficients of the domain basis
vector $\mathbf{e}_j$ mapped to the codomain $L (\mathbf{e}_j)$ in the codomain basis.  
$$
\begin{bmatrix}
d_{1}\\
d_{2}\\
\vdots\\
d_{m}
\end{bmatrix}
=
\begin{bmatrix}
a_{11} & a_{12}& \dots & a_{1n}\\
a_{21} & a_{22}& \dots & a_{2n}\\
\vdots & \vdots & \ddots & \vdots\\
a_{m1} &a_{m2} &\dots & a_{mn}
\end{bmatrix}
\begin{bmatrix}
c_{1}\\
c_{2}\\
\vdots\\
c_{n}
\end{bmatrix}
$$
Notice the shape of the matrix is $m\times n$

That is in some **specifically chosen bases** a linear map can be represented as matrix multiplication on the coordinates
of the vector in the domain basis. The matrix columns are the coordinates of the image of the domain basis vectors in
the codomain basis.

