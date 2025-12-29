# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
```
class Beans(): 
    def type(self):
        print("Vegetable") 
    def color(self):
        print("Green") 
class Mango(): 
    def type(self): 
        print("Fruit") 
    def color(self): 
        print("Yellow")      
def func(obj):
    obj.type()
    obj.color()
obj_beans = Beans() 
obj_mango = Mango() 
func(obj_beans) 
func(obj_mango)
```
## Output
<img width="448" height="223" alt="image" src="https://github.com/user-attachments/assets/70ab0713-2c3a-4049-8be4-a858f7c7bd59" />


## Result
Thus, the python program to create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism has been executed successfully.
