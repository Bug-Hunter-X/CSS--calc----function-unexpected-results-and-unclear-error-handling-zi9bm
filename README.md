# CSS calc() Unexpected Behavior

This repository demonstrates a common issue with the CSS `calc()` function where unexpected behavior can occur due to the order of operations and unit handling. The issue is not immediately apparent and can lead to debugging challenges.

The `bug.css` file contains the CSS code that demonstrates the problem.  The `bugSolution.css` file offers a solution, explaining the cause and providing a more robust approach.

## Problem Description

The `calc()` function, while powerful, can be problematic when it involves percentages and other units. In scenarios where the parent element's width is not explicitly defined, or where the calculation results in an invalid or unexpected value, the rendering result may not be as intended.

## Solution

The solution involves careful consideration of the order of operations and providing necessary context (explicit parent width or alternate calculation). The solution file demonstrates alternative approaches for more predictable results.