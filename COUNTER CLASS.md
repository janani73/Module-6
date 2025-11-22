# Exp.No:6b
## COUNTER CLASS - Operator Overloading in Python

### AIM 
To write a Python program that demonstrates operator overloading using the __gt__() method to compare two objects based on their values.

### ALGORITHM

```
1.Start
2.Create a class A with a constructor that stores a value
3.Define the method __gt__(self, other) to overload the greater than (>) operator
4.Inside the method, compare the values of the two objects
5.Create two objects: ob1 = A(2) and ob2 = A(3)
6.Use the expression ob2 > ob1 to invoke the overloaded operator
7.If the condition is true, print “ob2 is greater than ob1”
8.Otherwise, print “ob1 is greater than ob2”
9.End
```

### PROGRAM

```
class A:
    def __init__(self,value):
        self.value=value
    def __gt__(self,other):
        if self.value > other.value:
            return True
        else:
            return False
ob1=A(2)
ob2=A(3)

if ob2 > ob1:
    print("ob2 is greater than ob1")
else:
    print("ob1 is greater than ob2")
```

### OUTPUT

<img width="1205" height="282" alt="image" src="https://github.com/user-attachments/assets/ea4af7d1-fc65-4bc9-9062-6403d743200b" />

### RESULT
The program successfully demonstrates operator overloading.
