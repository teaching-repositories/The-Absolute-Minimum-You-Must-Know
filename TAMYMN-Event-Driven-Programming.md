# Event Driven Programming in Python: The Absolute Minimum You Must Know

Event driven programs respond to external events or inputs.

## Event Loop 

An event loop runs continuously waiting for events.

```python
while True:
  event = get_next_event()
  handle_event(event)
```

## Event Handlers

Define functions to handle specific event types.

```python
def handle_click(event):
  print("Button clicked")
```

## Register Handlers

Register handlers to listen for events.

```python
register_handler('click', handle_click) 
```  

## Event Queue

Events get added to a queue as they occur.

## Asynchronous

Handlers process events concurrently without blocking.

## Inputs as Events 

User clicks, keypresses etc can trigger events.

Event driven programs react to external triggers instead of controlling flow.