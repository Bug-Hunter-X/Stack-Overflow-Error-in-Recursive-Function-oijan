# Stack Overflow Bug in JavaScript

This repository demonstrates a common error in JavaScript: stack overflow caused by unbounded recursion. The `foo` function recursively calls itself without a proper base case for large inputs, leading to excessive function calls and eventual stack overflow.

The solution introduces iterative approach to prevent stack overflow.