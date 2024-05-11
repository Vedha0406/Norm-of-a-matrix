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
# Register No: VEDHASHREE G
# Developed By: 212223240171
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
![Screenshot 2024-05-11 131208](https://github.com/Vedha0406/Norm-of-a-matrix/assets/150884870/19bfd6a4-76b0-4551-af66-843de588c79b)

<br>
<br>
<br>

### 2-Norm of a Matrix!
![Screenshot 2024-05-11 131231](https://github.com/Vedha0406/Norm-of-a-matrix/assets/150884870/cd47bdfe-c7a0-493e-9725-f5c89dd447ed)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![Screenshot 2024-05-11 131251](https://github.com/Vedha0406/Norm-of-a-matrix/assets/150884870/e91cfad9-af14-4af6-a8f6-32c6a2afccad)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
