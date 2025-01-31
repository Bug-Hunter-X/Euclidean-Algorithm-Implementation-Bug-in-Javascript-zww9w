# Euclidean Algorithm Implementation Bug

This repository contains a JavaScript implementation of the Euclidean algorithm with a bug. The bug causes incorrect results for some inputs and throws a 'Maximum call stack size exceeded' error for others. The solution file provides a corrected version of the algorithm.

## Bug Description

The provided code uses recursion to find the GCD of two numbers. However, the base case for the recursion is incorrect. When one of the numbers is zero, it should return the other number, but the provided code either returns false or throws an error.

## Bug Solution

The bug is fixed by adding a correct base case to handle when one of the inputs is zero. Also, the check of the two numbers for equality has been improved to handle the edge case of zero values more gracefully.