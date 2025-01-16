# Unintended List Styling in CSS

This repository demonstrates a common yet easily overlooked CSS bug: unintended styling of list elements due to incorrect or missing selectors.  The issue arises from a selector that's too broad, applying styles to elements other than the intended target.

The `bug.css` file contains the buggy code.  The `bugSolution.css` file shows the corrected code.

## Bug Description:
The original CSS code mistakenly styles list items beyond the targeted unordered or ordered list, due to an improper or missing selector.