# :focus-visible CSS Pseudo-Class Inconsistency

This repository demonstrates a common issue with the `:focus-visible` CSS pseudo-class: inconsistent behavior across different browsers.  Older browsers lack support, which can lead to unexpected styling or accessibility problems.

The `focus-bug.css` file showcases the problematic code.  The `focus-solution.css` file provides a solution using feature detection and fallback styles.

## Solution

The solution involves detecting browser support for `:focus-visible` and applying different styles accordingly.  This ensures consistent behavior across all browsers while maintaining the intended user experience.

## How to Test

1. Clone the repository.
2. Open `focus-bug.html` and `focus-solution.html` in different browsers (including older ones if possible).
3. Observe the styling differences and the improved consistency in `focus-solution.html`.