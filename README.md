# Multiplying-two-matrix

## AIM:

## ALGORITHM:

### Step 1:
Start python program.

### Step 2:
Import numpy and Create two empty lists.

### Step 3:
Get two matrices from the user using append.

### Step 4:
Multipy the two matrices.

### Step 5:
Display the result.

## PROGRAM: 
~~~
#Name:M.Hariharan
#Ref.No:21005392
import numpy as np
l1,l2=[],[]
n=int(input())
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
X=np.array(l1)
Y=np.array(l2)
product=X*Y
print("Product of two arrays is:",product)
~~~

## OUTPUT:
![output](mult.png)

## RESULT:
A python program for Multipying two matrices has been created successfully.
