# CSS Specificity Gotcha: Identical Selectors, Unexpected Override

This repository demonstrates a subtle but important aspect of CSS specificity that can lead to unexpected behavior.  The bug showcases how two identical selectors, appearing later in the stylesheet, can override previous identical selectors.

## The Bug

The `bug.css` file contains CSS rules where identical selectors are declared multiple times.  The behavior is not intuitive and can be very hard to debug for those unfamiliar with the intricacies of CSS specificity. The key here is the order in which these selectors appear in the file.

## The Solution

The solution file `bugSolution.css` addresses the issue by explaining the problem and presenting approaches to avoid this type of conflict. This includes strategies for better CSS organization and the strategic use of the `!important` declaration (with appropriate caution).