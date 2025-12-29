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
class Rectangle:
    def __init__(self, length, width):
        self.__length = length 
        self.__width = width   
    
    def print_values(self):
        print(self.__length)
        print(self.__width)

r = Rectangle(5, 3)
r.print_values()

```
## Output
<img width="339" height="68" alt="image" src="https://github.com/user-attachments/assets/f2729d83-8015-4503-b275-cd1af24bc9f8" />

## Result
Thus, we were successfully able to implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.
