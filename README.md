# MongoDB $inc Operator with String Value

This example demonstrates an incorrect usage of MongoDB's `$inc` operator, where a string value is provided instead of a number.  The `$inc` operator is designed to increment a numeric field by a specified value.  Using a string leads to unexpected behavior.  This repository showcases the problem and its solution.

## Bug
The `bug.js` file contains code with the incorrect usage of `$inc`.

## Solution
The `bugSolution.js` file provides the correct implementation using a numeric value.

## How to reproduce
1. Clone the repository
2. Run `bug.js` to observe the incorrect behavior.
3. Run `bugSolution.js` to see the corrected result.