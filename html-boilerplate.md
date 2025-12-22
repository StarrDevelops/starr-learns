# HTML Foundations: The Boilerplate

The HTML boilerplate is the "Standard Operating Procedure" (SOP) for every web page. It establishes the environment and metadata required for a browser to render content accurately and safely.

## 1. The Declaration: `<!DOCTYPE html>`
* **Function:** A mandatory instruction that tells the browser the document is written in HTML5.
* **Note:** It is a declaration, not an element, and does not require a closing tag.

## 2. The Root: `<html>`
* The container for the entire document.
* Usually includes the `lang="en"` attribute to assist screen readers and search engines with language detection.

## 3. The Manifest: `<head>`
The `<head>` contains metadata—information *about* the page that isn't visible on the "bench" (the main window).
* **`<meta charset="utf-8">`:** Ensures universal character encoding (prevents text corruption).
* **`<meta name="viewport" content="width=device-width, ...">`:** Ensures the site scales correctly on mobile devices.
* **`<title>`:** Defines the text shown in the browser tab.

## 4. The Bench: `<body>`
* All visible content (headings, paragraphs, images, links) must reside within the `<body>` tags.