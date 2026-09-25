---
title: Example of Coordinate Change of a Linear Map
template: default
---
 
Let us calculate the matrix this in numpy
```python
import numpy as np

P = np.array([[1, 1],
              [1, -1]])
A = np.array([[1, 2],
              [3, 4]])


new_matrix = np.linalg.inv(P) @ A @ P

print(new_matrix)

[[ 5. -1.]
 [-2.  0.]]
``` 
