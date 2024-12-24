# CSS Float Issue: Inconsistent Div Width with Undefined Parent Width

This repository demonstrates a common issue with using `float` in CSS when the parent container's width is not explicitly defined.  The problem and a solution are provided below.

## Problem

The `bug.css` file contains CSS that attempts to make two divs occupy 50% of their parent's width each using `float: left;`. However, this only works correctly if the parent container has a defined width. Otherwise, the divs will collapse and not fill the parent as expected.

## Solution

The `bugSolution.css` file offers a solution by using flexbox. Flexbox provides a more robust and reliable way to achieve the desired layout regardless of the parent container's width. The solution addresses the issue without needing to explicitly set the parent's width.

## How to reproduce

1. Clone this repository.
2. Open `index.html` (or create your own HTML with divs and link to the CSS files).
3. Observe the difference in behavior when using `bug.css` and `bugSolution.css`.