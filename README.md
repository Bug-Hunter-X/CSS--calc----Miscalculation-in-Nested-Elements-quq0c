# CSS `calc()` Miscalculation in Nested Elements

This repository demonstrates a common error involving the CSS `calc()` function and provides a solution. The bug arises from an incorrect usage of `calc()` within nested elements, leading to unexpected layout issues. The provided solution shows how to correctly use `calc()` to achieve the desired result.

## Bug
The `bug.css` file shows the incorrect usage of `calc()`. Specifically, the width calculation of a nested element doesn't account for the parent element's dimensions correctly. This results in the inner element not having the expected width.

## Solution
The `bugSolution.css` file demonstrates the correct usage of `calc()`.  By carefully considering the context of the calculation, the desired width is achieved reliably.