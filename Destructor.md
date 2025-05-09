# Exp.No:22  
## Destructor

---

### AIM  
To create a Python class `Student` with a destructor.

---

### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s1` of the `student` class. When the object `s1` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s1`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

---

### PROGRAM

```
#Name:Govarshini.P
#Reg No:212223020009

class Student:
    def __init__(self, name):
        print('Inside Constructor')
        self.name = name
        print('Object initialized')
    def show(self):
        print('Hello, my name is', self.name)
    def __del__(self):
        print("Inside destructor")
        print("Object destroyed")
s1 = Student('Emma')
s1.show()
del s1

```

### OUTPUT
![image](https://github.com/user-attachments/assets/6bf6d9a9-3939-4afa-8474-8fd35e420850)


### RESULT
Thus the Python class `Student` with a destructor is executed successfully.
