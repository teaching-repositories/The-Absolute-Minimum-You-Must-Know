# Doctest for Dummies: The Absolute Minimum You Must Know

Doctest allows testing Python code examples in documentation. Here is the basics:

## Docstrings

In a function docstring, add a code example:

```python
def func(x):
  """
  >>> func(5)
  10
  """
```

## Running Doctests

Test code examples in docstrings:

```
python -m doctest myfile.py
```

This will check if the docstring code outputs match.

## Test Results

Doctest will output the number of test cases and any failures.

## Assertions

Can also use asserts in examples:

```python
"""
>>> x = 5
>>> assert x == 5
"""
```

## Verbose Mode

Use verbose mode to see details on each tested example:

```
python -m doctest -v myfile.py
```

That covers the basics of validating code through doctstrings! Doctest is an easy way to test documentation.