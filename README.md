# CSS Specificity Bug: Unexpected Style Overriding

This repository demonstrates an uncommon bug related to CSS selector specificity. The bug showcases how a highly specific selector can unexpectedly override other style rules due to its higher specificity weight.

## Bug Description

The CSS code uses multiple selectors targeting the same element. However, a highly specific selector overrides the styles defined by less specific selectors, resulting in unexpected styling.

## Bug Reproduction

1. Clone this repository.
2. Open `bug.css` to see the problematic code.
3. Open `index.html` to visualize the unexpected behavior.

## Solution

The solution involves a better understanding of CSS specificity and restructuring the CSS rules to achieve the desired styling. View the `bugSolution.css` file for the corrected CSS code.