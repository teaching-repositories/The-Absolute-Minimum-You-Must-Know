# Data Structures in Python: The Absolute Minimum You Must Know

Python has built-in data structures for storing and organizing data.

## Lists

Lists store ordered, mutable sequences.

```python
numbers = [1, 2, 3]
numbers.append(4)
```

## Tuples 

Tuples are immutable, fixed-size lists.

```python
point = (3, 4)
```

## Dictionaries 

Dicts store key-value pairs.

```python
user = {'name': 'John', 'age': 25}
```

## Sets

Sets are unordered collections of unique elements.

```python
s = set([1, 2, 3])
```

## Stacks

LIFO data structure. Use lists or deque.

```python
stack = [1, 2, 3]
stack.append(4)
stack.pop()
```

## Queues

FIFO data structure. Use deque.

```python
from collections import deque

queue = deque([1, 2, 3])
queue.append(4)
queue.popleft() 
```

Python's built-in data structures cover common data modeling needs.