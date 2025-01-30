# CSS calc() Gotchas: Spaces and Units

This repository demonstrates two potential pitfalls when using the CSS `calc()` function:

1. **Spaces around operators:** Extra spaces around the `+`, `-`, `*`, and `/` operators can lead to unexpected results or even parsing errors in some browsers.
2. **Incompatible units:** Mixing different units (e.g., pixels and percentages) within a single `calc()` expression without proper unit conversion may result in unpredictable outcomes.

The `bug.css` file contains examples of these problematic `calc()` usages, while `bugSolution.css` shows the corrected versions.

This example highlights the importance of adhering to the `calc()` function's syntax and using units consistently to prevent layout issues and ensure cross-browser compatibility.