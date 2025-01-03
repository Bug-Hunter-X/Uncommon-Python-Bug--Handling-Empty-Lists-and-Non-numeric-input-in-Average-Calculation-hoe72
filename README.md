# Uncommon Python Bug: Average Calculation
This repository demonstrates an uncommon bug that can occur in Python when calculating the average of a list of numbers. The bug arises from the failure to handle edge cases such as empty input lists and lists containing non-numeric values.

## Bug Description
The `calculate_average` function does not explicitly handle the cases where the input list `numbers` is empty or contains elements that are not numbers. This leads to errors such as `ZeroDivisionError` (when the list is empty) or `TypeError` (when the list contains non-numeric values).

## Bug Reproduction
1. Run the `bug.py` script.
2. Observe the `ZeroDivisionError` when an empty list is passed to the function.
3. Observe the `TypeError` when a list with a non-numeric value is passed to the function. 

## Solution
The `bugSolution.py` script shows the corrected `calculate_average` function. This version includes error handling that addresses the aforementioned issues.