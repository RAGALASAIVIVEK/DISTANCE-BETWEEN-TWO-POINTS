# DISTANCE-BETWEEN-TWO-POINTS


## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: Import math
### Step 2: assign the values of two points
### Step 3: Substitute the values in the distance formula eig
### Step 4: Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: Print the values
### Step 5: End the program

### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: sai vivek ragala
#RegisterNumber:23003676
import math
def calculate_distance(x1, y1, x2, y2):
    distance = math.sqrt((x2 - x1)**2 + (y2 - y1)**2)
    return round(distance, 2)
x1,y1 = 4, 2
x2,y2= 10, 6
bridge_length = calculate_distance(x1, y1,x2, y2)
print(f"{bridge_length}")
```
### OUTPUT:
![Screenshot from 2023-10-28 17-28-19](https://github.com/RAGALASAIVIVEK/DISTANCE-BETWEEN-TWO-POINTS/assets/144979718/b7ec43bf-0674-4f7e-81b5-45ad9cb68264)


### RESULT:
Thus the distance between two points are successfully found.
