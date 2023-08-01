# Abstraction in Python: The Absolute Minimum You Must Know

Abstraction hides unnecessary details and exposes only essential features. 

## Abstract Classes

Declare abstract classes with `abc.ABC`:

```python
from abc import ABC

class Animal(ABC):
  pass
```

## Abstract Methods

Declare abstract methods that subclasses must implement:

```python
from abc import abstractmethod

class Animal(ABC):

  @abstractmethod
  def make_sound(self):
    pass

```

## Subclass Implementation

Subclasses then implement the abstract methods:


```python
class Dog(Animal):

  def make_sound(self):
    print("Bark!")
```

## Hide Details

Abstract away complex logic into simple method calls.

## Focus on Essentials

Reduce software complexity by isolating key behaviors.

Abstraction separates interfaces from implementation details.