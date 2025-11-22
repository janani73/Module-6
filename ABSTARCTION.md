# Exp.No:6a
## Abstraction - Program to demonstrate Polymorphism in Python using Classes and Methods.

### AIM  

To write a Python program that uses two different classes with the same method names to demonstrate polymorphism, where each object responds differently to the same method call.
### ALGORITHM
```
Start

Create a class Ferrari with methods fuel_type() and max_speed()

Create a class BMW with methods fuel_type() and max_speed()

Create objects for Ferrari and BMW

Store both objects inside a tuple named cars

Loop through each object in cars

Call fuel_type() method for each object

Call max_speed() method for each object

Stop
```


### PROGRAM

```
class Ferrari:
    def fuel_type(self):
        print("Petrol")

    def max_speed(self):
        print("Max speed 350")

class BMW:
    def fuel_type(self):
        print("Diesel")

    def max_speed(self):
        print("Max speed is 240")

ferrari = Ferrari()
bmw = BMW()
cars=(ferrari,bmw)
for car in cars:
    car.fuel_type()
    car.max_speed()

```

### OUTPUT
<img width="1207" height="360" alt="image" src="https://github.com/user-attachments/assets/29cd86c7-bbf6-47a6-b514-3f2462afb15c" />

### RESULT
The program successfully demonstrates polymorphism.
When each car object is iterated, it prints its own fuel type and maximum speed, showing different outputs for the same method names.
