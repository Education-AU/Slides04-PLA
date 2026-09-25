---
title: Example of Coordinate Change of a Linear Map
template: default
---
 
We need the change of coordinates matrix from the new basis $\mathbf{e}'_i$ to the standard basis $\mathbf{e}_i$. The columns of this matrix are the coordinates of the new basis vectors in terms of the old basis. So we have
$$
P_{e'\rightarrow e}=\begin{bmatrix}
1 & 1\\
1 & -1              
\end{bmatrix}
$$
From the formula we have
$$
d'=\left (P_{e\rightarrow e'}AP_{e\rightarrow e'}^{-1}\right)c'
$$
But since in this case the basis change matrix is simplest expresse from $e'\rightarrow e$

Whe have

$$
d'=\left (P_{e'\rightarrow e}^{-1}AP_{e'\rightarrow e}\right)c'
$$  

Which in matrix form is
$$
\begin{bmatrix}
d'_{1}\\
d'_{2}                  
\end{bmatrix}    
=
\begin{bmatrix}
1 & 1\\
1 & -1            
\end{bmatrix}^{-1}      
\begin{bmatrix}
1 & 2\\
3 & 4
\end{bmatrix}
\begin{bmatrix}
1 & 1\\
1 & -1      
\end{bmatrix}
\begin{bmatrix}
c'_{1}\\    
c'_{2}
\end{bmatrix}   
$$