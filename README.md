# Unexpected Behavior of calc() with Percentages in Media Queries

This repository demonstrates a CSS bug related to the unexpected behavior of the `calc()` function when used with percentage values inside media queries.  The issue is that the calculation does not seem to be performed correctly, resulting in the element's width remaining unchanged despite the use of `calc()`. 

The `bug.css` file contains the problematic CSS code, and `bugSolution.css` offers a potential solution.  See the README for details on how to reproduce the issue and the suggested workaround.

## Reproducing the Issue

1. Clone this repository.
2. Open `index.html` (which you will need to create) in your browser.
3. Resize your browser window to trigger the media query.
4. Observe that the element's width does not change as expected.

## Solution

The solution may involve avoiding percentage values within the `calc()` function inside the media query. This can be achieved by using absolute units or other calculation methods that do not rely on percentage-based values.  See `bugSolution.css` for a possible solution.