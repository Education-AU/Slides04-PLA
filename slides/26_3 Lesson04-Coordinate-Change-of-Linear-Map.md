---
title: Coordinate Change of a Linear Map
template: default
---

We rewrite the $c$ coordinates to be expressed in the new basis $\mathbf{e}'_i$ of $V$.
$$
d=Ac=A \left (P_{e'\rightarrow e}c'\right)
$$
Where $P_{e'\rightarrow e}$ is the matrix changing coordinates from $\mathbf{e}'_i$ to $\mathbf{e}_i$ of $V$. That is
the columns of $P_{e'\rightarrow e}$ are
the coordinates of the $\mathbf{e}'_i$ basis int the $\mathbf{e}_i$ basis.

We typically want to use the change from $\mathbf{e}_i$ to $\mathbf{e}'_i$ instead which is the inverse
of $P_{e'\rightarrow e}$. That is we have $P_{e\rightarrow e'}^{-1}=P_{e'\rightarrow e}$. So we get

$$
d=A\left (P_{e\rightarrow e'}^{-1}c'\right)
$$
Similarly we can rewrite the $d$ coordinates to be expressed in the new basis $\mathbf{f}'_j$ of $W$.
$$
Q_{f\rightarrow f'}^{-1}d' = A\left (P_{e\rightarrow e'}^{-1}c'\right)
$$
so we get
$$
d'=\left (Q_{f\rightarrow f'}AP_{e\rightarrow e'}^{-1}\right)c'
$$
If $V=W$ we have $Q_{f\rightarrow f'}=P_{e\rightarrow e'}$ and we get
$$
d'=\left (P_{e\rightarrow e'}AP_{e\rightarrow e'}^{-1}\right)c'
$$  

