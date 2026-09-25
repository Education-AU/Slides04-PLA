---
title: Inverse of linear maps
template: default
---

Can we prove that the inverse of a linear map is linear

<div class="h3-blue">
The inverse of a linear map is linear
</div>

Let $L:V \to W$ and the inverse $L^{-1}:W \to V$

Consider $\mathbf{w}_1,\mathbf{w}_2 \in W$

Since $L$ is surjective by assumption there are $\mathbf{v}_1,\mathbf{v}_2 \in V$ such that $L(\mathbf{v}_1)=\mathbf{w}_1,L(\mathbf{v}_2)=\mathbf{w}_2$. 

This implies

$$
\begin{aligned}
L^{-1}(\mathbf{w}_1+\mathbf{w}_2)=L^{-1}(L(\mathbf{v}_1)+L(\mathbf{v}_2)) =\\
L^{-1}(L(\mathbf{v}_1+\mathbf{v}_2))=\mathbf{v}_1+\mathbf{v}_2\\
=L^{-1}(\mathbf{w}_1)+L^{-1}(\mathbf{w}_2)
\end{aligned}
$$

And similarly for scalar multiplication
$$
L^{-1}(c\mathbf{w}_1)=L^{-1}(cL(\mathbf{v}_1))=L^{-1}(L(c\mathbf{v}_1))=c\mathbf{v}_1=cL^{-1}(\mathbf{w}_1)
$$

