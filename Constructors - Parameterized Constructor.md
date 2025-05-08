# Exp.No:21  
## Constructors - Parameterized Constructor

---

### AIM  
To write a Python code to create a class for a person with a parameterized constructor, which will take the `name` and `userid` of the person as parameters and print the details using  def display(self) method.

---

### ALGORITHM

1. Begin the program.  
2. Define a `person` class.  
3. The `person` class should have a parameterized `__init__` method that accepts two parameters: `name` and `userid`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `id` to `self.id`.  
5. Print the `self.id`.  
6. Prompt the user to enter their `name` (string) and `userid`.  
7. Create an instance `s1` of the `person` class by passing the entered `name` and `userid` to the constructor.
8. Implement display(self) to print the name and id. 
9. Terminate the program.

---

### PROGRAM

```
#Name:Govarshini.P
#Reg No:212223020009

class Teacher:
    def __init__(self,id,name):
        self.name=name
        self.id=id
        
    def display(self):
        print(f"Hello my id is : {self.id}")
        print(f"My name is : {self.name}")
t=Teacher(int(input()),input())
t.display()
```

### OUTPUT
![image](https://github.com/user-attachments/assets/6039d681-706c-451e-9472-59caca81284a)

### RESULT
Thus the python program to print the details with the parameterized constructors using def display(self) method is executed successfully.
