# 231.-Power-of-Two
# Java Recursion – Power of Two

This repository contains Java programs related to recursion.
Currently, it includes a solution to check whether a number is a power of 2.

## Problem
Given an integer `n`, determine whether it is a power of two.

## Approach
- If `n == 1`, return true
- If `n <= 0` or `n` is odd, return false
- Otherwise, divide `n` by 2 and repeat recursively

## Example
Input: 16  
Output: true  

Input: 10  
Output: false  

## Time Complexity
O(log n)

## File
- `powerOfTwo.java`
