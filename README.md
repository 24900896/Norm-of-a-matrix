# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	

Step 1:
Import the required library (numpy) for matrix operations.

Step 2:
Input the matrix using the np.array() function with eval(input()).

Step 3:
Use the np.linalg.norm() function to calculate the norm of the matrix:
For 1-norm, pass ord=1 as the argument (or directly use np.linalg.norm(matrix, 1)).
For 2-norm, pass ord=2 (or directly use np.linalg.norm(matrix, 2)).
For infinity norm, calculate the maximum row sum using np.max(np.sum(np.abs(matrix), axis=1)).

Step 4:
Format the result to two decimal places using "{:.2f}".format() or f-string.

Step 5:
Print the result.
## Program:


# Register No:212224230239
# Developed By:S.Sandeep
# 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/34276462-e526-4ce9-ab7d-109c4877d6d5)




# 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/31c50c8c-7bab-472b-80a4-e0b01f56b435)




# Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/4f4071bf-8082-4579-be83-f5c6fd00974f)
```




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/36543bf9-8bf5-4d15-94bb-c3ae92babe15)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/b0d79a7e-e1d2-42a4-9027-328a0e50d5c3)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/7fa39cda-6ba0-488a-bba3-f83073f137ca)
```

Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
