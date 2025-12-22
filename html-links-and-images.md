# HTML Foundations: Links and Images

Links and images turn static text into a "Web." They rely heavily on attributes to function and require specific security and accessibility considerations.

## 1. Anchor Elements (`<a>`)
Links are created using the anchor tag. They are not functional without the `href` attribute.
* **`href`**: The destination URL (Hypertext Reference).
* **`target="_blank"`**: Opens the link in a new tab.
* **Security**: When using `target="_blank"`, use `rel="noopener"` to prevent the new page from accessing the original window's JavaScript object. Use `rel="noreferrer"` only if you wish to hide the source of the traffic.

## 2. Image Elements (`<img>`)
Images are "void" elements (self-closing). 
* **`src`**: The path to the image file (Source).
* **`alt`**: Alternative text for screen readers and as a fallback if the image fails to load. This is a requirement for accessible, professional code.

## 3. Pathing Logic
* **Absolute Links**: Full URLs (e.g., `https://google.com`). Used for external sites.
* **Relative Links**: Links to files within your own project.
    * `./` : Current directory.
    * `../` : Move up one parent directory.

## 4. Standard Image Formats
* **JPG**: Best for complex photographs.
* **PNG**: Best for images requiring transparency.
* **GIF**: Best for simple animations.
* **SVG**: Best for logos and icons (vector-based).