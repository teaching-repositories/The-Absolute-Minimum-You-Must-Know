# TDD in Python for Dummies: The Absolute Minimum You Must Know

Test-driven development means writing tests before code. Here are the steps:

## 1. Write a Failing Test 

Write a test asserting expected behavior that fails:

```python
import unittest

class TestClass(unittest.TestCase):
  def test_uppercase(self):
    self.assertEqual(func('hello'), 'HELLO')
```

## 2. Run the Test

The new test should fail since the code hasn't been written yet:

```
unittest.main()
```

## 3. Write Code 

Add the minimum amount of code to pass the test:

```python
def func(input):
  return input.upper()
```

## 4. Re-run the Test

The test should now pass with the new code:

```
unittest.main()
```

## 5. Refactor

Clean up code, while re-running tests to ensure they still pass.

## Repeat the Cycle

Go back to step 1 and iterate!

This TDD cycle of red-green-refactor ensures code quality and test coverage.