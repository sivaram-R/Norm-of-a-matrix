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
# Register No:22008680
# Developed By:sivaram R
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
![1norm](https://user-images.githubusercontent.com/121165794/214517654-43fcddf6-af03-499c-a32a-a3771f9d0473.png)

### 2-Norm of a Matrix

![2 norm](https://user-images.githubusercontent.com/121165794/214517848-742f9ea8-ba04-4f4b-9137-5fe54210775d.png)

### Infinity Norm of a Matrix
![Screenshot (53)](https://user-images.githubusercontent.com/121165794/214518239-790f0ae8-7d5c-40ce-afba-ccda53a74984.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
