---
title: Exercise 1 Solution
template: two-column
showFooter : false
---

#### Exercise a

$ T (x,y)= (2x-y,\ x+3y)$

$T[(x_1,y_1)+ (x_2,y_2)]=T (x_1+x_2,y_1+y_2)= (2 (x_1+x_2)- (y_1+y_2), (x_1+x_2)+3 (y_1+y_2))$

$= (2x_1-y_1, x_1+3y_1)+ (2x_2-y_2, x_2+3y_2)=T (x_1,y_1)+T (x_2,y_2)$

and

$T (c (x,y))=T (cx,cy)= (2 (cx)-cy, cx+3 (cy))=c (2x-y, x+3y)=cT (x,y)$

so T is linear.

#### Exercise b

$T (x,y)= (x+y+1,\ 2x-y)$

$T[(x_1,y_1)+ (x_2,y_2)]=T (x_1+x_2,y_1+y_2)= (x_1+x_2+y_1+y_2+1, 2 (x_1+x_2)- (y_1+y_2))$

$=T (x_1,y_1)+T (x_2,y_2)+ (-1,0)$

so it cannot be linear

#### Exercise c

$ T (c (x,y))=T (cx,cy)= (cx)(cy)=c^2xy=c^2T (x,y)$

So for this cannot be linear

<!-- column -->

##### Exercise d

$T (x,y,z)= (x+2y-z,\ 3x+y+2z)$

$T (1,0,0)= (1,3)$

$T (0,1,0)= (2,1)$

$T (0,0,1)= (-1,2)$

Then the matrix is
$$
A=\begin{pmatrix}1&2&-1\\3&1&2\end{pmatrix}
$$

$$
T (1,2,-1)=\begin{pmatrix}1&2&-1\\3&1&2\end{pmatrix}\begin{pmatrix}1\\2\\-1\end{pmatrix}=\begin{pmatrix}1+4+1\\3+2-2\end{pmatrix}=\begin{pmatrix}6\\3\end{pmatrix}
$$ .

#### Exercise e

$$
T\begin{pmatrix}1\\0\end{pmatrix}
=\begin{pmatrix}1\\2\\-1\end{pmatrix},
\qquad
T\begin{pmatrix}0\\1\end{pmatrix}
=\begin{pmatrix}3\\0\\2\end{pmatrix}.
$$
Then the matrix is 
$$
A=\begin{pmatrix}1&3\\2&0\\-1&2\end{pmatrix}
$$