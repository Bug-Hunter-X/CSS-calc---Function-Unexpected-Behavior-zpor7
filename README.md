# CSS `calc()` Function Unexpected Behavior

This repository demonstrates an uncommon issue with the CSS `calc()` function. Specifically, it highlights problems that can occur when combining percentages with other units (like pixels) within the `calc()` function and using nested `calc()` functions.  The problem is not consistently reproducible across all browsers and versions, making it a tricky bug to diagnose.

## Reproduction Steps

1. Clone this repository.
2. Open `bug.css` and examine the problematic CSS rules.
3. Open `bug.html` (or create your own HTML file that includes the `bug.css` stylesheet).
4. Observe the layout and note the unexpected behavior.
5. Compare the behavior with the corrected CSS in `bugSolution.css`.