# stableset

A C-Extension type for Python that provides a set implementation that is stable on iteration.

## Installation

```bash
pip install retracesoftware.stableset
```

## Usage

```python
import retracesoftware.stableset as stableset

# Create a stable set
s = stableset.set([1, 2, 3, 4, 5])

# Iteration order is stable (consistent across runs)
for item in s:
    print(item)

# Standard set operations work as expected
s.add(6)
s.remove(1)
print(len(s))
```

## Features

- **Stable iteration order**: The order of elements when iterating over the set is consistent across runs
- **High performance**: C-extension implementation for optimal speed
- **Python 3.11+ compatible**: Built for modern Python versions
- **Cross-platform**: Works on macOS (Intel and Apple Silicon), Linux, and Windows

## License

This project is licensed under the Apache License, Version 2.0. See the [LICENSE](LICENSE) file for details.
