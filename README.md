# Uncommon CSS Bugs

This repository demonstrates two uncommon CSS bugs:

1. **Unexpected Overflow with `calc()` and Padding:** Using `calc()` to calculate width while including padding can lead to horizontal overflow if the content width exceeds the calculated width.
2. **Unpredictable Vertical Spacing with Percentage `line-height`:** Applying percentage `line-height` to an element containing images can result in inconsistent vertical spacing, misaligning images and text.

The `bug.css` file contains the problematic code, while `bugSolution.css` provides solutions to fix these issues.