# Remove Element

## Problem
Given an integer array nums and an integer val, remove all occurrences of val in nums in-place and return the number of elements not equal to val.

## Example

Input:
nums = [3,2,2,3]
val = 3

Output:
2

Explanation:
After removing 3, the first two elements become [2,2].

## Approach

Use the two pointer technique.

Traverse the array and copy elements that are not equal to val to the front of the array.

Time Complexity: O(n)
Space Complexity: O(1)

## Solution

See RemoveElement.cs
