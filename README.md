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

# 1-Norm of a Matrix
```
# Register No: Pravin raj.A
# Developed By: 212222240079


import numpy as np

mat= np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```

# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Pravin raj.A
RegisterNumber: 212222240079
'''
import numpy as np

mat= np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```



# Infinity Norm of a Matrix
```
#program to find the Infinity of a matrix and display the result in two decimal places.
#Developed by: Pravin raj.A
#Register No: 212222240079


import numpy as np

mat=np.array(eval(input()))
ans= np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```






## Output:
### 1-Norm of a Matrix
![Screenshot 2023-06-03 101129](https://github.com/Apravinraj/Norm-of-a-matrix/assets/118707879/2697571e-f8b4-4619-8d2d-f5f836d0c0fa)

### 2-Norm of a Matrix
![Screenshot 2023-06-03 101158](https://github.com/Apravinraj/Norm-of-a-matrix/assets/118707879/6ef6dcac-167c-49a6-8d11-e7a49ccaa7e9)

### Infinity Norm of a Matrix
![Screenshot 2023-06-03 101223](https://github.com/Apravinraj/Norm-of-a-matrix/assets/118707879/f1e77ef9-64b8-46f2-9d7e-61781b95a4c5)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
