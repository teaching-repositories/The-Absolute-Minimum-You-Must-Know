# Functions in Python: The Absolute Minimum You Must Know

Functions organize code into reusable blocks that can be called. Here's the basics:

## def Statements 

Define functions with the `def` keyword:

```python
def my_func():
  print("Hello")
```  

## Calling Functions

Call functions by name with parameters if needed:

```python
my_func()

def print_name(name):
  print(name)

print_name("John")
```

## return Statements

Return a value from the function with `return`: 

```python
def add(x, y):
  return x + y

result = add(3, 5) 
```

## Docstrings

Document functions using triple quotes below the def line:

```python
def my_func():
  """Explain what this does"""
```

## Scope

Variables inside functions are local scoped and isolated.

That's the core basics of using functions in Python! They are key to writing reusable, organized code.