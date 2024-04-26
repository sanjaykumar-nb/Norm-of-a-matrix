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

```
1-Norm of a Matrix
'''
program to find 1-norm of the matrix.
Developed by SANJAYKUMAR N B
register number: 212223230189
'''
import numpy as np

mat= np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



2-Norm of a Matrix
'''
program to find 1-norm of the matrix.
Developed by SANJAYKUMAR N B
register number: 212223230189
'''
import numpy as np

mat= np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


Ifinite-Norm of a Matrix
'''
program to find 1-norm of the matrix.
Developed by SANJAYKUMAR N B
register number: 212223230189
'''
import numpy as np

mat= np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![alt text](<Screenshot 2024-04-27 040927.png>)

### 2-Norm of a Matrix

![alt text](<Screenshot 2024-04-27 040945.png>)
### Infinity Norm of a Matrix
![alt text](<Screenshot 2024-04-27 040959.png>)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
