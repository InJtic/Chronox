# Chronox

`Chronox` is a powerful **timer** for measuring the execution time of Python functions!

## Performance Measurement

Measuring algorithm performance is a crucial aspect of software development.

`Chronox` logs function execution times, allowing users to analyze performance easily with the provided tools.

## Installation

You can install `Chronox` via `pip`:

```bash
pip install chronox
```

## Usage
Here’s how you can use Chronox:

```python
from chronox import timer
import matplotlib.pyplot as plt

@timer
def add(a, b):
    return a + b

# Print execution time logs
print(add.log)

# Visualize execution time
add.visualize()
plt.show()
```