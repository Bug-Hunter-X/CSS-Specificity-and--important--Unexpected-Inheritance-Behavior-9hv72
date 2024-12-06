# CSS Specificity and !important: An Uncommon Issue

This repository demonstrates an uncommon bug related to CSS specificity and the `!important` flag, specifically concerning inheritance and unexpected behavior.  The issue arises when a more specific selector is overridden by a less specific selector with `!important`.

The `bug.css` file contains the problematic code. The `bugSolution.css` file offers a solution demonstrating best practices to avoid such issues.  Generally, avoiding `!important` is good practice for maintainability and predictability.