# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
```
class A:
    def __init__(self,a):
        self.a=a
    def __gt__(self,other):
        return self.a > other.a
        
ob1=A(20)
ob2=A(3)

if ob1>ob2:
    print("ob2 is less than ob1")
else:
    print("ob1 is less than or equal to ob2")


```

## Output

![Screenshot 2025-05-20 174839](https://github.com/user-attachments/assets/35853c7f-3b7b-44d1-8632-78df1d02c9b6)

## Result
Thus, python program that demonstrates operator overloading by overloading the less than (<) operator using a custom class is executed successfully.
