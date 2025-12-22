# HTML Foundations: Lists

Lists are used to group related pieces of information together. They are essential for both visual organization and accessibility.

## 1. Unordered Lists (`<ul>`)
* Used for a collection of items where the order does not matter.
* Displays with bullet points by default.

## 2. Ordered Lists (`<ol>`)
* Used for a sequence of items where the order is significant (e.g., instructions, rankings).
* Displays with numbers/letters by default.
* **Attributes:** Can use `start` to change the beginning number or `reversed` for a countdown.

## 3. List Items (`<li>`)
* The "atoms" of a list. 
* A `<ul>` or `<ol>` container must only contain `<li>` elements as direct children.

## 4. Nesting Lists
* To create a sub-list (e.g., a "Batch" under a "Project"), the sub-list must be placed inside an `<li>` element of the parent list.
* Example:
  <li>Parent Item
    <ul>
      <li>Sub-item</li>
    </ul>
  </li>