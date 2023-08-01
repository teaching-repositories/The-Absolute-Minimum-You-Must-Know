# Classes in Python: The Absolute Minimum You Must Know 

Python classes provide object-oriented programming capabilities. Here's the basics:

## Class Definitions

Define classes with the `class` keyword:

```python
class MyClass:
  x = 5
```

## Constructors 

The `__init__()` method is called on initialization:

```python
class Person:
  def __init__(self, name): 
    self.name = name
```  

## Instance Objects

Create object instances from a class:

```python
p1 = Person("John")
print(p1.name)
```

## Class Methods

Define class methods using `def`:

```python
class Math:
  def add(self, x, y):
    return x + y
```

## Inheritance

Inherit from other classes by passing the parent class:

```python
class Student(Person):
  pass
```

That covers basic class syntax and object-oriented principles in Python! Classes allow code reuse through inheritance and abstraction.