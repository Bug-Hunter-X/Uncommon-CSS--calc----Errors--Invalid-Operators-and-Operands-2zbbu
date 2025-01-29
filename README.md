# Uncommon CSS `calc()` Errors

This repository demonstrates a common yet often overlooked error involving the CSS `calc()` function: using invalid operators or operands.

The `calc()` function is powerful but requires careful attention to detail. Incorrect use can lead to unexpected rendering and layout problems that are difficult to track down.

## Bug Description

The `bug.css` file contains a demonstration of invalid `calc()` usage. Mixing incompatible units within a single `calc()` expression (like `px` and `%`) can cause unexpected results. Similarly, using an unsupported operator or an invalid operand can lead to errors.

## Solution

The `bugSolution.css` file provides the corrected code with the proper unit usage.  Always ensure unit consistency within the `calc()` expression and use valid operators and operands.

## Reproduction

1. Clone this repository.
2. Open `bug.html` in a web browser (you may need to create a simple HTML file to test the CSS).
3. Observe the incorrect layout.
4. Replace `bug.css` with `bugSolution.css` and see the corrected layout.