# Visualizing: The Absolute Minimum You Must Know

Pandas is a Python library used for data analysis and visualization. Here's an introduction to visualizing data with Pandas:

## Importing Pandas

Import Pandas and matplotlib for plotting:

```python
import pandas as pd
from matplotlib import pyplot as plt
```

## Read in Data 

Read data from a CSV into a Pandas DataFrame:

```python 
df = pd.read_csv("data.csv")
```

## Basic Plotting

Create simple plots from DataFrame columns:

```python
df['column'].plot()
df.plot.bar(x='col1', y='col2')
```

## Customizing Plots

Customize plots by adding titles, axis labels, legend, etc:

```python
plt.title("My Plot")
plt.xlabel("x-axis")
plt.legend()
```

## Saving Plots 

Save plots to image files using `.savefig()`:

```python
plt.savefig("plot.png")
```

That covers basic Pandas plotting! You can now load data, generate plots, customize them, and save visualizations.