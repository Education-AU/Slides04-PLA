---
title: Matrix representation of a Linear map
template: default
---


We now apply $L$ to $\mathbf{v}$
$$
L(\mathbf{v})=\sum_{j=1}^n c_jL(\mathbf{e}_j)
$$
$ L(\mathbf{e}_j)$ can be expanded in the **chosen** basis of the $m$-dimensional codomain $W$
$$
L(\mathbf{e}_j)=\sum_{i=1}^m a_{ij}\mathbf{f}_i
$$
So the map in its entirety is
$$
L(\mathbf{v})=\sum_{j=1}^n c_j \sum_{i=1}^m a_{ij}\mathbf{f}_i=\sum_{i=1}^m \left(\sum_{j=1}^n a_{ij}c_j\right) \mathbf{f}_i 
$$
