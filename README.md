# CSS calc() Space Issue
This repository demonstrates a common but easily overlooked bug in CSS: forgetting to include spaces around the plus (+) and minus (-) operators when using the `calc()` function.

The issue arises when performing calculations directly within the `calc()` function without providing the necessary spacing around the operators. This can lead to unexpected results or cause the calculation to fail entirely.

The example shows an incorrect implementation where there are missing spaces around the minus operator, resulting in an incorrect width calculation. The corrected version includes the necessary spaces, ensuring the calculation is performed accurately.  It is essential to maintain this spacing in CSS calculations for consistency and correctness.

## How to reproduce
1. Open `bug.css` and examine the incorrect usage of the `calc()` function.
2. Open `bugSolution.css` to view the corrected code.
3. Observe the difference in the computed width between the two versions in a browser's developer tools or by visually comparing the layout.