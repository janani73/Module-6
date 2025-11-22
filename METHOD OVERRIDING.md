# Exp.No:6d 
## Method Overriding - Object-Oriented Programming in Python – Employee Class Example
### AIM  
To demonstrate the creation and usage of a class in Python, including constructors, methods, and accessing object data members.
### ALGORITHM
```
1.Start
2.Define a class named Employee.
3.Inside the class, define a constructor __init__ that initializes name, salary, and project.
4.Create a method show() to display the employee’s name and salary.
5.Create another method work() to display what project the employee is working on.
6.Create an object s of the Employee class and pass the values "Jessa", 8000, "NLP".
7.Call the show() method using the object s to display name and salary.
8.Call the work() method using the object s to display the project.
9.End
```
### PROGRAM

```
class Employee:
    # constructor
    def __init__(self, name, salary, project):
        self.name = name
        self.salary = salary
        self.project = project
    def show(self):
        # accessing public data member
        print("Name: ", self.name, 'Salary:', self.salary)

    # method
    def work(self):
        print(self.name, 'is working on', self.project)

s=Employee("Jessa",8000,"NLP")
s.show()
s.work()
```

### OUTPUT
<img width="1206" height="298" alt="Screenshot 2025-11-22 233443" src="https://github.com/user-attachments/assets/c516b6f6-8f05-4c89-8a1a-39992a397692" />


### RESULT
Thus, the program successfully demonstrates how an employee object can be created, how its data members can be accessed, and how its methods can be used to display information and work details.
