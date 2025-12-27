# Knowledge Log: CSS Box Model
**Project/Lesson:** TOP Foundations - Box Model
**Date:** 2025-12-27
**Stakeholder:** @StarrDevelops

## Key Concepts
* **The Order:** Content (inner) > Padding > Border > Margin (outer).
* **Box-Sizing:** * `content-box` (Standard): Width/Height only applies to content; padding/border make the box grow.
    * `border-box` (Alternative): Width/Height includes padding/border; content shrinks to fit. Recommended for all projects.
* **Layout:**
    * `margin: auto` centers block elements.
    * Negative margins allow for overlapping.
    * `display: inline-block` allows blocks to sit side-by-side while respecting dimensions.

## Verified Insights
* Margin collapsing: Only the largest margin between two elements is applied.
* Padding: Cannot be negative; creates space inside the background/border.