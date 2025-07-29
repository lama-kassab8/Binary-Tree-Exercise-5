# Symmetric Tree

This project contains a Python solution to the [LeetCode Symmetric Tree problem](https://leetcode.com/problems/symmetric-tree/).

## Problem Description

Given the `root` of a binary tree, check whether it is a mirror of itself (i.e., symmetric around its center).

## Approach

The solution uses recursion. A helper function `isMirror(left, right)` checks whether two subtrees are mirrors of each other by comparing:

- Both being `None` (symmetric)
- One being `None` while the other is not (not symmetric)
- Their root values being equal
- Recursively checking their outer and inner children:
  - `left.left` vs `right.right`
  - `left.right` vs `right.left`

  ## Status

✅ Successfully passed all test cases on LeetCode.
