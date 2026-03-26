# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.


## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.



## 💻 Program
~~~

class Rectangle:
    
    def __init__(self, length, breadth):
        self.__length = length
        self.__breadth = breadth

        print("Length:", self.__length)
        print("Breadth:", self.__breadth)


rect = Rectangle(10,5)
~~~

## Output
Length: 10
Breadth: 5


## Result
The program successfully demonstrates encapsulation in Python. The private member variables __length and __breadth are accessible only within the class. When the object is created, the constructor initializes and displays their values, showing how encapsulation protects data from direct external access.
