---
title: Linear Map Properties
template: default
---

Some immediate properties of linear maps are

<div class="center">

1. **Origin maps to origin**<br>
$L(\mathbf{0})=L(0\mathbf{0})=0L(\mathbf{0})=\mathbf{0}$
2. **Additive inverse preserved**<br>
$L(-\mathbf{v})=L(-1\mathbf{v})=-1L(\mathbf{v})=-L(\mathbf{v})$
3. **Lines through origin are preserved**<br>
$L(s\mathbf{v})=sL(\mathbf{v})$
4. **Subspaces are preserved**<br>
If $U\subset V$ is a subspace $L(U) \subset W$ is a subspace.
5. **The kernel is a subspace of $V$**<br>
Let $\mathbf{v}_1,\mathbf{v}_2 \in Ker(L)$ and $c_1,c_2 \in \mathbb{F}$. Then $L(c_1\mathbf{v}_1+c_2\mathbf{v}_2)=c_1L(\mathbf{v}_1)+c_2L(\mathbf{v}_2)=c_1\mathbf{0}+c_2\mathbf{0}=\mathbf{0}$.
6. **The range is a subspace of $W$**<br>
Let $\mathbf{w}_1,\mathbf{w}_2 \in Range(L)$ and $c_1,c_2 \in \mathbb{F}$. Then $\mathbf{w}_1=L(\mathbf{v}_1)$ and $\mathbf{w}_2=L(\mathbf{v}_2)$ for some $\mathbf{v}_1,\mathbf{v}_2 \in V$. Therefore, $c_1\mathbf{w}_1+c_2\mathbf{w}_2=c_1L(\mathbf{v}_1)+c_2L(\mathbf{v}_2)=L(c_1\mathbf{v}_1+c_2\mathbf{v}_2) \in Range(L)$.

</div>