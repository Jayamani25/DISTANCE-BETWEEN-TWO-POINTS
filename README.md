# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
From the problem write the points in x axis separately
### Step 2: 
From the problem write the points in y axis separately
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.jpg)
### Step 4: 
By using square function in math module we can take square root 
### Step 5: 
print the output
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: R.Jayamani
#RegisterNumber: 22008124
import math as m
l1=[4,2]
l2=[10,6]
d=m.sqrt((l2[0]-l1[0])**2+((l2[1]-l1[1])**2))
print("{:.2f}".format(d))
```

### OUTPUT:
![Distance](https://user-images.githubusercontent.com/85949888/209547094-213131be-fbab-48f1-a886-4ebef53f9892.png)


### RESULT:
Thus the distance between two points is executed successfully.
