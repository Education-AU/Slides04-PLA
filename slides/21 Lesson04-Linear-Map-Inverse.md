---
title: Inverse of maps
template: default
---

We need to formally define when a map is invertible. This requires two concepts, and they hold for any map not just linear map.

Let $L:V \to W$ be a map

1. The map is **surjective**<br>
   This means that every target in $W$ is hit by a vector in $V$
   $$
   \forall \mathbf{w} \in W ,\exists \mathbf{v} \in V: L (\mathbf{v})=\mathbf{w}
   $$
2. The map is **injective**<br>
   This means that two different vectors in $V$ cannot produce the same image by $L$
   $$
   L (\mathbf{v}_1)=L (\mathbf{v}_2)\Rightarrow \mathbf{v}_1=\mathbf{v}_2
   $$

If these two conditions are met the map is said to be **bijective** and thereby invertible.

