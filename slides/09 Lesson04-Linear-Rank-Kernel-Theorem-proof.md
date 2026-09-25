---
title: Rank-Kernel or Rank-Nullity theorem
template: default
---

<div class="h3-blue">
Proof:
</div>
Assume $\{\mathbf{v}_1,\dots,\mathbf{v}_k\}$ is a basis for $\operatorname{ker} (L)$ and extend it to a basis $\{\mathbf{v}_1,\dots,\mathbf{v}_k,\mathbf{v}_{k+1},\dots,\mathbf{v}_n\}$ for $V$. 

Then $\{L (\mathbf{v}_{k+1}),\dots,L (\mathbf{v}_n)\}$ is a basis for $\operatorname{range} (L)$.

Assume $\mathbf{w} \in \operatorname{range} (W)$, then $\mathbf{w}=L (\mathbf{v})$ for some $\mathbf{v}\in V$.
Then $\mathbf{v}=\sum_{i=1}^{n}a_i\mathbf{v}_i$ for some $a_i\in \mathbb{F}$

But then $\mathbf{w}=L (\mathbf{v})=\sum_{i=k+1}^{n}a_iL (\mathbf{v}_i)$ since $L (\mathbf{v}_i)=0$ for $i=1,\dots,k$.
Hence $\mathbf{w}$ is a linear combination of $\{L (\mathbf{v}_{k+1}),\dots,L (\mathbf{v}_n)\}$

The set $\{L (\mathbf{v}_{k+1}),\dots,L (\mathbf{v}_n)\}$ is linearly independent.

Assume $\sum_{i=k+1}^{n}a_iL (\mathbf{v}_i)=0$ for some $a_i\in \mathbb{F}$.

Then $L (\sum_{i=k+1}^{n}a_i\mathbf{v}_i)=0$ and hence $\sum_{i=k+1}^{n}a_i\mathbf{v}_i \in \operatorname{ker} (L)$.
But $\{\mathbf{v}_1,\dots,\mathbf{v}_k\}$ is a basis for $\operatorname{ker} (L)$ and
hence $\sum_{i=k+1}^{n}a_i\mathbf{v}_i=\sum_{i=1}^{k}b_i\mathbf{v}_i$ for some $b_i\in \mathbb{F}$. But
then $\sum_{i=1}^{k}b_i\mathbf{v}_i-\sum_{i=k+1}^{n}a_i\mathbf{v}_i=0$ and
since $\{\mathbf{v}_1,\dots,\mathbf{v}_k,\mathbf{v}_{k+1},\dots,\mathbf{v}_n\}$ is a basis for $V$, we must have $a_i=0$
for $i=k+1,\dots,n$.
Then

so we have shown that $\{L (\mathbf{v}_{k+1}),\dots,L (\mathbf{v}_n)\}$ is a basis for $\operatorname{range} (L)$ and hence
$$
\operatorname{dim} (\operatorname{ker} (L))+\operatorname{dim} (\operatorname{range} (L))=k+ (n-k)=n=\operatorname{dim} (V)
$$
