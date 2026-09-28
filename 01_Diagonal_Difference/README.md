# Diagonal Difference

## Problem Description

Given a square matrix, calculate the absolute difference between the sums of its primary diagonal and secondary diagonal.

## Approach

1. Find the size of the square matrix.
2. Traverse the matrix using a single loop.
3. Add the elements of the primary diagonal.
4. Add the elements of the secondary diagonal.
5. Return the absolute difference between the two diagonal sums.

## Example

Matrix:

11  2   4
4   5   6
10  8  -12

Primary diagonal:

11 + 5 + (-12) = 4

Secondary diagonal:

4 + 5 + 10 = 19

Absolute difference:

|4 - 19| = 15

## Complexity Analysis

- Time Complexity: O(N)
- Space Complexity: O(1)

## HackerRank Status

Accepted