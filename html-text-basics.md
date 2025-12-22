# HTML Foundations: Working with Text

Text in HTML is about more than just display; it is about providing structure and meaning (Semantics) to the content for both browsers and accessibility tools.

## 1. Structural Text Elements
* **Paragraphs (`<p>`):** Wraps blocks of text. Browsers automatically add vertical space (margin) between paragraphs.
* **Headings (`<h1>` - `<h6>`):** Used to create a document hierarchy. `<h1>` is the primary title, while `<h2>` through `<h6>` represent sub-sections of decreasing importance.
* **Line Breaks (`<br>`):** A void element used to start a new line within a block of text without starting a new paragraph.

## 2. Lists (Data Grouping)
* **Unordered List (`<ul>`):** Groups items using bullet points. Used when the sequence doesn't change the meaning.
* **Ordered List (`<ol>`):** Groups items using a numerical sequence. Used for steps, rankings, or protocols.
* **List Item (`<li>`):** The required child element for every item inside a list.

## 3. Emphasis and Importance
* **`<strong>`:** Indicates that the text has high importance or urgency. Browsers render this as **bold** by default.
* **`<em>`:** Indicates emphasis (like a change in tone of voice). Browsers render this as *italics* by default.
* **Note:** These are preferred over `<b>` and `<i>` because they provide semantic meaning for screen readers.

## 4. Document Relationships
* **Parent/Child:** An element nested inside another (e.g., `<li>` is a child of `<ul>`).
* **Siblings:** Elements at the same level of nesting.
* **Comments (``):** Notes for developers that are not rendered by the browser.