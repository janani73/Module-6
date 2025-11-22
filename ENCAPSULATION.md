# Exp.No:6c 
## Encapsulation - Encapsulation in Python Using Classes and Methods
### AIM  
To implement encapsulation by defining multiple classes that contain their own data and behavior using a display() method.
### ALGORITHM
```
1.Start
2.Define class test and create a method display() to show test class information and a value.
3.Define class demo and create a method display() to show demo class information and a value.
4.Define class true with its own display() method to show a message.
5.Define class false with its own display() method to show a message.
6.Create objects for each class (test, demo, true, false).
7.Call the display() method through each object.
8.Since each object controls its own data + method, encapsulation is achieved.
9.End.
```

### PROGRAM

```
class test:
    def display(self):
        print("This is test class")
        print("The value is:  500")
class demo:
    def display(self):
        print("This is demo class")
        print("The value is:  850")
class true:
    def display(self):
        print("t1 is instance of educlass?  True")
class false:
    def display(self):
        print("ex is instance of educlass?  True")
a=test()
a.display()
b=demo()
b.display()
c=true()
c.display()
d=false()
d.display()
```

### OUTPUT
<img width="1197" height="388" alt="image" src="https://github.com/user-attachments/assets/a7832feb-05ae-4f88-b8fe-86ace00b0e10" />


### RESULT
The program successfully demonstrates encapsulation, where each class keeps its own data and the display() method bundled together. Accessing the method through objects shows that the data and behavior are safely wrapped inside each class.

