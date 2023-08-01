# Encapsulation in Python: The Absolute Minimum You Must Know

Encapsulation bundles data and methods into a single unit. 

## Classes 

Classes bundle together related attributes and methods.

```python
class Person:

  def __init__(self, name):
    self.name = name
```

## Data Hiding

Prefix private attributes with underscores.

```python 
class Person:

  def __init__(self, name):
    self._name = name
```

## Getters and Setters

Control access to attributes with getters and setters.

```python
class Person:

  def get_name(self):
    return self._name

  def set_name(self, value):
    self._name = value
```

## Restrict Access 

Prevent direct access to attributes. Use getters and setters.

## Maintain Valid States

Setters can validate data before allowing changes.

Encapsulation controls and protects object data.