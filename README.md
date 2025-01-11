# TypeScript Type Error: 'string[]' is not assignable to type 'string'

This repository demonstrates a common TypeScript error: assigning an array of strings to a variable expecting a single string.

## Bug

The `greeter` function expects a single string argument. However, the code attempts to pass an array of strings to this function.

## Solution

The solution involves either modifying the `greeter` function to accept an array of strings or iterating through the array and calling the `greeter` function for each string in the array.