# Knowledge Log: Flexbox Axes
**Project/Lesson:** TOP Foundations - Axes
**Date:** 2026-01-05
**Stakeholder:** @StarrDevelops

## Key Concepts
* **Flex-Direction:** Determines the 'Main Axis'. 
    * `row` (default): Main Axis is horizontal.
    * `column`: Main Axis is vertical.
* **Flex-Basis Recontextualization:** * In a row, `flex-basis` acts as the ideal width.
    * In a column, `flex-basis` acts as the ideal height.
* **Axis Independence:** `justify-content` always follows the Main Axis, regardless of its physical orientation.

## Verified Insights
* `flex-basis` is axis-dependent, not dimension-dependent.
* Switching to `column` is the primary method for responsive stacking.