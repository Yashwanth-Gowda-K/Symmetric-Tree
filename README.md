# Symmetric-Tree
Symmetric Tree - LeetCode Problem #101

This repository contains the solution to **LeetCode Problem 101: Symmetric Tree**, implemented in Python.
🧩 Problem Statement
Given the `root` of a binary tree, **check whether it is a mirror of itself (i.e., symmetric around its center).**


The solution uses **recursion** to compare the left and right subtrees.  
The key idea is to check:

1. If both nodes are `None`, it's symmetric.
2. If only one is `None`, it's not symmetric.
3. If values are equal, recursively check:
   - `left subtree of left tree` vs `right subtree of right tree`
   - `right subtree of left tree` vs `left subtree of right tree`
