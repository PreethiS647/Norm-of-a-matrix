# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:
# Developed By:
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-06 195316](https://github.com/PreethiS647/Norm-of-a-matrix/assets/147313372/28396259-9342-4727-b949-2303903bfda9)


### 2-Norm of a Matrix
![Screenshot 2024-05-06 195334](https://github.com/PreethiS647/Norm-of-a-matrix/assets/147313372/648e6284-4244-4829-81d9-d23704a97008)

### Infinity Norm of a Matrix
![Screenshot 2024-05-06 195349](https://github.com/PreethiS647/Norm-of-a-matrix/assets/147313372/e743d81f-f18c-44ac-b1ce-8a6272152701)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
