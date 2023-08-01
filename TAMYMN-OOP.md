# OOP in Python: The Absolute Minimum You Must Know

Object-oriented Python focuses on objects that contain data and behavior. 

## Classes and Objects

A class defines attributes and methods. An object is an instance.

```python
class Person:
  def __init__(self, name):
    self.name = name

p = Person('Jane')
```

## Encapsulation 

Bundle data with methods that operate on that data.

## Inheritance

Child classes inherit attributes and methods from parents.

```python
class Student(Person):
  pass
```

## Polymorphism

Child classes can override methods from the parent.

## Abstraction

Hide internal details with abstract classes. Focus on essentials.

## Composition 

Objects can contain other objects rather than inheriting directly.

OOP allows modeling real-world entities and relationships in code.