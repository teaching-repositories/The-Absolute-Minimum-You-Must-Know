# Testing in Python: The Absolute Minimum You Must Know

Testing helps catch bugs and validate code behavior in Python. Here's the basics:

## unittest

The unittest module is the standard for Python testing. Import it to get started.

```python
import unittest
```

## Test Class 

Create a class inheriting from `unittest.TestCase` to hold tests:

```python
class TestClass(unittest.TestCase):
```

## Test Methods

Write test methods starting with `test_` that call assert methods:

```python  
def test_valid_input(self):
  self.assertEqual(func(3), 4)
```

## assert Methods

Common asserts include:

- `assertEqual(a, b)` - a == b
- `assertTrue(x)` - x is True  
- `assertFalse(x)` - x is False
- `assertRaises(error)` - raises error

## Running Tests

Run tests with:

```
unittest.main()
```

That covers basic Python unit testing! You can now validate code and prevent regressions.