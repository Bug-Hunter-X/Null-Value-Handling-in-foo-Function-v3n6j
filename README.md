# Null Value Handling Bug in JavaScript Function

This repository demonstrates a common bug in JavaScript related to handling null values. The `foo` function does not explicitly check for null values, leading to potential issues.

## Bug Description
The `foo` function does not handle null values passed as arguments. This can cause unexpected behavior or errors depending on how the function is used.

## Bug Reproduction
1. Clone this repository.
2. Run the `bug.js` file.
3. Observe that the function throws an error when a null value is passed as an argument.

## Solution
The `bugSolution.js` file shows a solution that explicitly checks for null values before processing them.