Here is an example README file for your scatterplot package:

# Scatterplot

A customizable scatter plot package for Python.

## Installation

```bash
pip install scatterplot
```

## Usage

```python
from scatterplot import scatter

x = [1, 2, 3, 4]
y = [2, 4, 1, 3]

# Basic plot
scatter(x, y) 

# Custom colors
colors = ['red', 'green', 'blue', 'black']
scatter(x, y, c=colors)

# Size by y-value 
sizes = [10, 20, 5, 30]
scatter(x, y, s=sizes) 

# Colormap 
scatter(x, y, s=y, cmap='viridis')
```

## Features

- Simple interface with sensible defaults
- Customize colors, sizes, alpha, marker style 
- Size markers by value for bubble charts
- Colormaps for continuous sizes/colors
- Pass through any matplotlib scatter kwargs

## Development

Clone the repo and install in editable mode:

```bash
git clone https://github.com/yourusername/scatterplot.git
cd scatterplot
pip install -e .
```

Run tests with:

```bash 
python -m tests.test_scatterplot
```

## License

The MIT License (MIT)

Copyright (c) 2023 Sameh Salah
```
