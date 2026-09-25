---
title: Inverse of maps
template: default
---

Invertible maps provide a perfect correspondence between two vectorspaces.
Every output is mapped from exactly one input, and every input is mapped to a unique output.

Let us assume we have a map 
$$
L:V\to W
$$ 
between two vectorspaces $V$ and $W$. If the map is invertible, we can then define the inverse map $L^{-1}:W\to V$ such that

$$
L^{-1}(L(\mathbf{v}))=I_{V}\mathbf{v},\quad \forall \mathbf{v}\in V
$$ 
and
$$
L(L^{-1}(\mathbf{w}))=I_{W}\mathbf{w},\quad \forall \mathbf{w}\in W
$$

Where $I_{V}$ and $I_{W}$ are the identity maps on $V$ and $W$ respectively.

This can be expressed in maps as
$$
L^{-1}\circ L=I_{V},\quad L\circ L^{-1}=I_{W}
$$