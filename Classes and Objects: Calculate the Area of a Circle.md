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


import math

# Define class
class cse:
    def mech(self, r):
        area = math.pi * r * r
        print("Area of the circle:", area)

# Get user input
radius = float(input("Enter radius: "))

# Create object and call method
obj = cse()
obj.mech(radius)


## Output

<img width="517" height="167" alt="image" src="https://github.com/user-attachments/assets/0f86e900-3c8b-4d3a-983e-458f1c9c069b" />


## Result

Thus, the Python program successfully calculates the area of a circle using a class and method based on the user-provided radius.
