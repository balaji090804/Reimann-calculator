# Riemann Sum Calculator

This is a Python project that calculates the Riemann sum for a given function over a specified interval using user inputs. The calculator supports left, right, and midpoint methods for the Riemann sum.

## Features

- **User Input:** Allows users to input the function to integrate, interval bounds, interval size, and the Riemann sum method.
- **Methods Supported:** Left, right, and midpoint Riemann sums.
- **Symbolic Function Parsing:** Uses `sympy` to parse and evaluate user input for the function.

## Requirements

- Python 3.x
- `numpy` library
- `sympy` library

You can install the required libraries using pip:
`bash
pip install numpy sympy`

You can run the file:
`bash
python riemann_sum_calculator.py`

##Example input method:

Enter the function to integrate (in terms of x): sqrt((x + 1)**7)
Enter the lower bound: 3
Enter the upper bound: 4
Enter the interval size: 0.2
Enter the method (left, right, midpoint): right

