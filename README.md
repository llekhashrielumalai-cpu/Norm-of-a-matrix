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
# Register No:25008477
# Developed By:LEKHASHRI E
# 1-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,1)
print(norm)
Program to find 2-norm of a matrix.
Developed by: lekhashri E
RegisterNumber: 25008477
'''




# 2-Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
n=f"{a:.2f}"
print(n)



# Infinity Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
n=f"{a:.2f}"
print(n)




```
## Output:
### 1-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot (109)" src="https://github.com/user-attachments/assets/5f0a8af2-cae9-4583-997a-92bb50453ea6" />
 

### 2-Norm of a Matrix
<br>
<img width="1920" height="1080" alt="Screenshot (110)" src="https://github.com/user-attachments/assets/54926f80-bdc0-47fe-b96e-7c6a890e3409" />

<br>
<br>

### Infinity Norm of a Matrix
<br>
<img width="1920" height="1080" alt="Screenshot (111)" src="https://github.com/user-attachments/assets/106e070c-3610-4a77-b881-8d58f011b06a" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
