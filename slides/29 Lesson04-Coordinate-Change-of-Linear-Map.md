---
title: Example of Coordinate Change of a Linear Map
template: default
---

So, the linear map in the new coordinates is
$$
A'=
\begin{bmatrix}
5 & -1\\
-2 & 0            
\end{bmatrix}
$$
We can verify this by calculating the image of a vector in the new coordinates and comparing it to the image in the old
coordinates.

Let us choose some vector in the new coordinates $c'=(1,2)$ which in the old basis is $c=(3,-1)$

The image of new coordinates under the new matrix is
$$
d'=
\begin{bmatrix}
5 & -1\\
-2 & 0
\end{bmatrix}
\begin{bmatrix}
1\\
2
\end{bmatrix}
=
\begin{bmatrix}
3\\
-2
\end{bmatrix}    
$$
In the old coordinates the image is
$$
d=
\begin{bmatrix}
1 & 2\\
3& 4
\end{bmatrix}
\begin{bmatrix}
3\\
-1
\end{bmatrix}
=
\begin{bmatrix}
1\\
5
\end{bmatrix}    
$$
And converting the image in the new coordinates back to the old coordinates we confirm the result
$$
3(1,1)-2(1,-1)=(1,5)          
$$