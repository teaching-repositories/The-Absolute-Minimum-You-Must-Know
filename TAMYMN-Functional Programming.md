# Functional Programming in Python: The Absolute Minimum You Must Know

Functional programming focuses on functions that don't modify state. Here are some key concepts:

## Pure Functions

Functions always return the same result for the same inputs. No side effects.

```python
def add(x, y):
  return x + y
```

## Immutability

Data is immutable and cannot be changed in-place.

```python
my_tuple = (1, 2, 3) # Tuples are immutable
```

## Avoid Side Effects

Don't modify state - return new objects instead.

## First-Class Functions

Treat functions like variables. Pass them as args.

```python
def apply(f, x):
  return f(x)
```

## Higher-Order Functions

Functions can accept/return other functions.

```python
def decorate(fn):
  return lambda x: "[]" + fn(x) + "[]"
```

## Recursion

Functions can call themselves. Useful for flow control.

```python 
def factorial(n):
  if n == 1: 
    return 1
  else:
    return n * factorial(n-1)
```

These concepts encourage declarative, reusable code in Python.