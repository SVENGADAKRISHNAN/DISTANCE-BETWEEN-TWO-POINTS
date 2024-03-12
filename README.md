#DISTANCE-BETWEEN-TWO-POINTS
##AIM:
To write a python program to find the distance two 2 points

##ALGORITHM:
###Step 1:
Using import math function,do the calculations.

###Step 2:
Take the two coordinates as l1 and l2.

###Step 3:
Substitute the values in the distance formula  ![formula](/formula.JPG)

###Step 4:
using the print function, display the distance between the two points.

###Step 5:
End the program.

##PROGRAM:
```
#subtract the (l2[0]-l1[0]) ^2 0 position add with (l2[1]-l1[1])^2 
#Developed by : S.Vengada Krishnan
#Reference no : 212223110061
import math as ma
l1=[4,2]# it is a list here
l2=[10,6]
d=ma.sqrt(((l2[0]-l1[0])**2)+((l2[1]-l1[1])**2))
print(f"{d:.2f}")
```

###OUTPUT:
![distance between two points](https://github.com/SVENGADAKRISHNAN/DISTANCE-BETWEEN-TWO-POINTS/assets/147473084/1cb4e541-ad29-4fe3-8731-c6eae88735e9)

###RESULT:
Thus the distance of the two points is sucessfully executed and displayed.
