# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Robot(object):
   def __init__(self):
      self.__version = 22

   def getVersion(self):
       return self.__version

   def setVersion(self, version):
      self.__version = version

obj = Robot()
print(obj.getVersion())
obj.setVersion(23)
print(obj.getVersion())
```
## Output
<img width="699" height="306" alt="image" src="https://github.com/user-attachments/assets/aaaab266-ffeb-41b5-8bce-40715f44efd4" />

## Result
Thus, the program has been executed successfully.
