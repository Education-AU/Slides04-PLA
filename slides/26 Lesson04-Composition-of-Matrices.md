---
title: Composition of a Linear map by matrices
template: default
---

Consider finite dimensional vectorspaces with given dimensions $(U,n), (V,m), (W,k)$ and maps

$$
\begin{aligned}
T_1 &: U \to V \\
T_2 &: V \to W
\end{aligned}
$$

Then the composition of maps $T_1$ and $T_2$

$$
\begin{aligned}
T_2\circ T_1 &: U\to W
\end{aligned}
$$

Can be represented in **coordinates**, **in some specific bases**, as the matrix product of the individual
matrices. That is

$$
\begin{aligned}
T_1 &: v=A_1^{mn}u \\
T_2 &: w=A_2^{km}v
\end{aligned}
$$
Where the shapes are as indicated. Then

$$
\begin{aligned}
T_2\circ T_1: w=A_2^{km}A_1^{mn}u
\end{aligned}
$$
