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
# Register No: 23010259
# Developed By: Abbu Rehan
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot (153)](https://github.com/Abburehan/Norm-of-a-matrix/assets/138849336/f5a7425f-5ca4-4f5d-b858-8ee679417966)

### 2-Norm of a Matrix
![Screenshot (153)](https://github.com/Abburehan/Norm-of-a-matrix/assets/138849336/57928bb2-933d-4990-a491-30be5b5e165d)

### Infinity Norm of a Matrix
![Screenshot (155)](https://github.com/Abburehan/Norm-of-a-matrix/assets/138849336/bd8744d6-6302-47a1-b3bc-ce9f04039c7b)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
