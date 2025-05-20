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
    __length = 0
    __breadth = 0
    def __init__(self,length,breadth):
        self.__length = 5
        self.__breadth = 3
    def show(self):
        print(self.__length)
        print(self.__breadth)
            
rect = Rectangle(5,3)
rect.show()


```

## Output
![Screenshot 2025-05-20 173741](https://github.com/user-attachments/assets/53789592-ee05-48d9-b564-2a7706a836a4)


## Result
Thus,defining a class Rectangle with private member variables __length and __breadth is executed successfully.
