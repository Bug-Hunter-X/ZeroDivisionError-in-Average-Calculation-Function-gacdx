# Python Bug: ZeroDivisionError in Average Calculation

This repository demonstrates a common yet easily overlooked error in Python: the `ZeroDivisionError` that can occur when calculating the average of an empty list.

The file `calculate_average.py` contains the buggy code, which doesn't handle the case where the input list `numbers` is empty.  The file `calculate_average_solution.py` provides a corrected version.

The issue arises because `len(numbers)` evaluates to 0 when the list is empty, leading to division by zero.  The solution involves adding a check for an empty list before performing the division.