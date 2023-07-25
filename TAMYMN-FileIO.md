# File IO: The Absolute Minimum You Must Know

Here are the key concepts for working with files in Python:

## Open a File

Use `open()` to open a file for reading or writing:

```python
file = open('data.txt', 'r') 
file = open('data.txt', 'w')
```

'r' = read mode, 'w' = write mode

## Read a File

Use `.read()` or iterate through lines in the file: 

```python 
contents = file.read()

for line in file:
  print(line)
```

## Write to a File

Use `.write()` to write to the open file:

```python
file.write('Hello world') 
```

## Append to a File

Open with 'a' mode to append instead of overwrite:

```python
file = open('data.txt', 'a')
file.write('This is appended text')
```

## Close a File

Always close an open file when finished:

```python
file.close()
```

That covers basic file I/O in Python! You can now open, read, write, and close files in Python programs.