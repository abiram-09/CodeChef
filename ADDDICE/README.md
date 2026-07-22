# ADDDICE - Adding Dice

## Problem Summary
Given the value of the first die, determine whether the second die can have a value such that the sum of both dice is exactly 9.

## Approach
- Compute the required value for the second die:
  - `Y = 9 - X`
- If `Y` is between `1` and `6`, print `YES`.
- Otherwise, print `NO`.

## Time Complexity
O(1)

## Space Complexity
O(1)
