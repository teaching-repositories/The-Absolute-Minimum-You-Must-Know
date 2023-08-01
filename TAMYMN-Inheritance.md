# Inheritance in Python: The Absolute Minimum You Must Know

Inheritance allows new child classes to inherit attributes and methods from parent classes.

## Parent Classes

Define a parent class with attributes and methods:

```python
class Vehicle:

  def __init__(self, make, model):
    self.make = make 
    self.model = model
  
  def info(self):
    return f"{self.make} {self.model}"

```

## Child Classes 

Inherit from parent class by passing it in:


```python
class Car(Vehicle):
  pass

my_car = Car("Toyota", "Corolla")
```

## Inherited Attributes 

Child class instances get parent attributes:

```python
print(my_car.make) # "Toyota"
```

## Inherited Methods

Child classes inherit parent class methods:

```python 
print(my_car.info()) # "Toyota Corolla"
```

## Override Methods

Child classes can override inherited methods:

```python
# Add custom logic
```

Inheritance reduces code duplication by reusing parent class code.