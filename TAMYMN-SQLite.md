# SQLite: The Absolute Minimum You Must Know

SQLite is a lightweight SQL database that can be easily used in Python applications. Here's what you need to know to get started with SQLite and Python:

## Import sqlite3

Import the `sqlite3` module to work with SQLite databases:

```python
import sqlite3
```

## Connect to a Database 

Connect to an existing DB or create a new one:

```python
conn = sqlite3.connect('my_database.db')
```

## Create a Cursor

Create a cursor to execute SQL commands:

```python
c = conn.cursor()
``` 

## Execute SQL 

Use the cursor to execute INSERT, SELECT, UPDATE, DELETE statements:

```python
c.execute("SELECT * FROM table")
```

## Commit Changes

Commit changes using `conn.commit()`:

```python
conn.commit()
```

## Close Connection

Close the connection when finished:

```python  
conn.close()
```

That covers the basics of using SQLite and SQL with Python! You can now connect to databases, create tables, query and manipulate data.