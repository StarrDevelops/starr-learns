# HTML Foundations: Elements, Tags, and Text

## 1. Anatomy of an HTML Element
In web development, the **Element** is the fundamental building block. It follows a strict "Zero-Error" syntax to ensure the browser interprets the structure correctly.

* **Opening Tag:** `<tagname>` - Marks the beginning of an element.
* **Content:** The data or text held within.
* **Closing Tag:** `</tagname>` - Marks the end. 
* **Attributes:** Metadata added to the opening tag (e.g., `<a href="...">`) to provide extra instructions.

## 2. Void (Self-Closing) Elements
Some elements do not wrap around content and therefore do not require a closing tag. 
* **Common Examples:** `<img>`, `<br>`, `<input>`, and `<meta>`.
* **Logic:** These are self-contained "samples" that represent an object rather than a container for text.

## 3. Text Hierarchy & Semantics
Choosing tags is not about visual style (which belongs to CSS), but about **Semantic Meaning**.

### Headings (`<h1>` through `<h6>`)
* `<h1>` represents the most critical information (the "Title").
* Headings must follow a logical hierarchy; skipping levels (e.g., going from `<h1>` to `<h3>`) breaks the document structure for accessibility.

### Lists: Ordered vs. Unordered
* **Unordered List (`<ul>`):** Used for collections where sequence does not change the meaning (bullet points).
* **Ordered List (`<ol>`):** Used for sequences where the order is vital to the result (e.g., a PCR protocol or chemical assay).
* **List Items (`<li>`):** The individual "aliquots" inside the parent list container.

## 4. Nesting and Integrity
Elements must be closed in the reverse order they were opened (Last-In, First-Out). Improper nesting leads to "cascading failures" in the visual layout.