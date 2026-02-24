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
# Register No:212225240104
# Developed By:Pavan Kalyan P

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

<img width="976" height="201" alt="image" src="https://github.com/user-attachments/assets/288c3381-36eb-44b2-aeaf-aac104fb588b" />


### 2-Norm of a Matrix

<img width="541" height="202" alt="image" src="https://github.com/user-attachments/assets/622a2a54-ff32-4dc3-8598-3666f40b3ee5" />


### Infinity Norm of a Matrix

<img width="802" height="145" alt="image" src="https://github.com/user-attachments/assets/302b0a97-ef45-408e-adf3-d394f5523576" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
