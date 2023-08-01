# Composition in Python: The Absolute Minimum You Must Know

Composition allows objects to contain other objects.

## Has-a Relationship

Composition expresses a has-a rather than is-a relationship.

```python
class Car:

  def __init__(self, engine):
    self.engine = engine
```

## Object Instances 

The contained objects are instantiated separately.

```python
engine = Engine()
car = Car(engine)
```

## Delegating Behavior 

Methods can delegate tasks to the contained objects.

```python 
class Car:

  def start(self):
    self.engine.start()
```

## Flexible Design

New behaviors can be added by composing different objects.

## Loose Coupling

Changes to contained objects don't directly affect the container.

Composition allows building complex objects from simpler ones.