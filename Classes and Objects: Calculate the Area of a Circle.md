# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

~~~
import math
class Cse:
    def mech(self,radius):
        area=math.pi*radius*radius
        print(f"Area of circle: {area:.2f}")
r=int(input())
obj=Cse()
obj.mech(r)
~~~

## Output
<img width="825" height="225" alt="600724750-507144d6-f2a5-4b23-a386-0bd511fc51da" src="https://github.com/user-attachments/assets/3127a279-bc61-4782-a1bc-4361d8e206a6" />

## Result:
Thus to write a Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation is done successfully.
