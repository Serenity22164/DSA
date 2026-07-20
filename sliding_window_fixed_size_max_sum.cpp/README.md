# Maximum Sum Subarray of Size K

## Problem Statement
Given an array of integers and an integer `k`, find the maximum sum among all contiguous subarrays of size `k`.

## Approach
- Use the **Sliding Window** technique.
- Compute the sum of the first `k` elements.
- Slide the window one element at a time:
  - Remove the leftmost element from the sum.
  - Add the new rightmost element.
  - Update the maximum sum.

## Algorithm
1. Calculate the sum of the first `k` elements.
2. Store it as the current maximum.
3. Slide the window until the end of the array.
4. Return the maximum sum found.

## Time Complexity
- **O(n)**

## Space Complexity
- **O(1)**

## Concepts Used
- Sliding Window
- Arrays

## Solution
See `maximum_sum_subarray_of_size_k.cpp`.
