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
# Register No:212224240054
# Developed By:Harshavardhan.K.B
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
norm="{:.2f}".format(ans)
print(norm)


```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/f7344986-d4c8-4567-a125-bb8b84dca818)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/c46cbdc1-63cd-4864-9cb1-7647436b17e2)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/a5ffdc8e-b4be-428b-9f88-08f274b9cd8a)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
