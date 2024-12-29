# Unexpected `calc()` Behavior with Percentages and Viewport Units

This repository demonstrates an unexpected behavior of the `calc()` function in CSS when combining percentages and viewport units (e.g., `vw`, `vh`).  The calculated value is not what's expected based on standard mathematical operations.

The `bug.css` file contains the problematic CSS code, and `bugSolution.css` provides a solution (or workaround) to achieve the correct result.

## Issue Description

The primary issue occurs when trying to calculate a width or height based on a percentage of the viewport and then adding or subtracting another value that involves viewport units. This sometimes leads to an incorrect computed value.

## Solution

The solution might involve different approaches based on the specific scenario and desired outcome.  Common workarounds might include:

* Using JavaScript to dynamically calculate the value.
* Avoiding the problematic combination of units within `calc()` and using separate CSS rules with absolute values.
* Utilizing different CSS techniques (such as flexbox or grid layout) that avoid the need for such complex calculations.

Please refer to `bugSolution.css` for a possible solution for this particular example.