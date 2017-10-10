# Quadratic equation solver

A small module for solving quadratic equation

# How to use

**_get_roots(a, b, c)_**

The function gets 3 coefficients of a quadratic equation and returns 2 values:
1. None, None - if there are no real roots 
2. root1, root2 - if there are 2 different roots
3. root, None - if there are 2 equal roots  

### Example
```python
from quadratic_equation import get_roots

if __name__ == '__main__':
    try:
        a, b, c = [int(x) for x in input().split()]
        print(get_roots(a, b, c))
    except ValueError:
        print('Check input data')
```

# How to launch tests

A script requires python 3.5 interpreter

This command launch tests on Linux:

```bash
python tests.py # may be required python3 instead of python
```

The launching on Windows is the similar.

# Project goals

The code is written for educational purposes. Training course for web-developers ― [DEVMAN.org](https://devman.org)
