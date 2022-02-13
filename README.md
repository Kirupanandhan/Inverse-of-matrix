# Inverse-of-matrix

## AIM:
To write a python program for finding the inverse of a matrix
## ALGORITHM:
### Step 1:
Import Numpy as np
### Step 2:
Create two empty lists and two variables for getting the values from the user.
### Step 3:
Create a nested loop and iterate the values.
### Step 4:
Find the inverse using np.linalg.inv() build in function.
### Step 5:
Print the values


## PROGRAM:
```
import numpy as np
l1, l2 = [],[]
r,c= int(input()),int(input())
for i in range(r):
    for j in range(c):
        num=int(input())
        l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)
value1= np.array(l2)
inverse = np.linalg.inv(value1)
print(inverse)
```
## OUTPUT:
![pic3](https://user-images.githubusercontent.com/94386222/153753816-0c5f3413-fe1d-4e82-b040-4febd3e837ca.png)

## RESULT:
Thus the program is Written and executed for finding the inverse of a matrix
