# JavaScript Undefined 'length' Property Error

This repository demonstrates a common error in JavaScript where attempting to access the `length` property of an undefined value results in a runtime error.  The `bug.js` file contains the erroneous code, while `bugSolution.js` provides a corrected version that handles undefined inputs gracefully.  This is crucial for robust JavaScript applications to avoid unexpected crashes.

## Problem

The original code fails to explicitly handle cases where the input (`x`) is undefined.  Attempting to read `x.length` when `x` is undefined throws a TypeError: 'Cannot read properties of undefined (reading 'length')'.

## Solution

The solution adds a check for undefined input before accessing the `length` property, ensuring that the function does not throw an error for unexpected input.