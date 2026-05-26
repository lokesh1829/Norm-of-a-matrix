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
# Register No:212225240080
# Developed By:Lokesh K
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
x="{:.2f}".format(ans)
print(x)




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="1314" height="532" alt="image" src="https://github.com/user-attachments/assets/cb8bcb3d-1e87-42d9-bf63-87ce43108a5d" />


### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1358" height="588" alt="image" src="https://github.com/user-attachments/assets/0c0670d7-0717-41e4-b114-46490fe63357" />


### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1362" height="571" alt="image" src="https://github.com/user-attachments/assets/16ae01b7-631a-4e1d-913b-d5ceec01f0df" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
