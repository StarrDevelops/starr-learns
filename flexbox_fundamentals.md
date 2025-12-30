# Knowledge Log: Flexbox Fundamentals
**Project/Lesson:** TOP Foundations - Flexbox & Growth
**Date:** 2025-12-30
**Stakeholder:** @StarrDevelops

## Key Concepts
* **Main Axis Logic:** Controlled by `flex-direction`. `justify-content` manages the Main Axis; `align-items` manages the Cross Axis.
* **Flex Components:**
    * `flex-grow`: Ratio for distributing extra space.
    * `flex-shrink`: Ratio for shrinking when space is insufficient.
    * `flex-basis`: The default size of an item before growing/shrinking occurs.
* **The Shorthand:** `flex: [grow] [shrink] [basis]` is the professional standard for conciseness.

## Verified Insights
* `flex: 1 1 0` creates equal-width columns regardless of content volume.
* In `flex-direction: column`, vertical alignment is handled by `justify-content`.