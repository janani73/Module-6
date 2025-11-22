# Exp.No:6e  
## Operator Overloading - Object-Oriented Programming in Python – Student Class Example

### AIM  
To demonstrate how to define a class with multiple methods in Python and how to call these methods using an object of the class.
### ALGORITHM
```
1.Start
2.Define a class named student.
3.Inside the class, define three methods:
  display() – to print student details.
  type() – to print a message for invalid roll number.
  types() – to print updated student details.
4.Create an object s of the class student.
5.Call the display() method using s to show student details.
6.Call the type() method using s to display the invalid roll number message.
7.Call the types() method using s to show updated student details.
8.End
```


### PROGRAM

```
class student:
    def display(self):
        print("Student Details: Jessa 10")
    def type(self):
        print("Invalid roll no. Please set correct roll number")
    def types(self):
        print("Student Details: Jessa 25")
s=student()
s.display()
s.type()
s.types()
```

### OUTPUT
<img width="1206" height="322" alt="image" src="https://github.com/user-attachments/assets/9f8d1712-9d94-4043-85d9-b9f4e1ad1fe7" />


### RESULT
Thus, the program successfully demonstrates how a student object can call multiple methods to display details, handle an invalid roll number scenario, and update or show revised information.
