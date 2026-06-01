Method Overriding-Fish and Shark Class Inheritance in Python
🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class Fish with a method type, and a child class Shark that overrides the type method.

📋 ALGORITHM:
Define the Fish class with a method named type() that prints "fish".
Define the Shark class as a subclass of Fish, and override the type() method to print "shark".
Create an instance of the Fish class named obj_goldfish.
Create an instance of the Shark class named obj_hammerhead.
Use a for loop to iterate over both objects.
Within the loop, call the type() method using the loop variable.
Output will demonstrate method overriding: printing "fish" and "shark" accordingly.
💻 PROGRAM:
class Fish:
    def water(self):
        print("fish")
       

class Shark:
    def water(self):
        print("shark")
	

obj_goldfish=Fish()
obj_hammerhead=Shark()

obj_goldfish.water()
obj_hammerhead.water()
OUTPUT
image
RESULT
Thus, the program has been executed successfully.
