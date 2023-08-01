# Matplotlib for Dummies: The Absolute Minimum You Must Know

Matplotlib is the main Python plotting library. Here are the basics:

## Importing 

Import matplotlib.pyplot:

```python
import matplotlib.pyplot as plt
```

## Simple Plot

Plot a line graph from data:

```python
x = [1, 2, 3]
y = [4, 5, 6] 

plt.plot(x, y)
```

## Showing Plots

Display the plot with `plt.show()`:

```python
plt.show() 
```

## Saving Plots 

Save plots with `plt.savefig()`:

```python
plt.savefig('plot.png')
```

## Customizing Plots

Customize with title, axes labels, etc:

```python
plt.title("My Plot")
plt.xlabel("X Axis")
```

That covers basic matplotlib plotting in Python! You can create, show, save and customize a variety of plot types.