# CSS How To
This section explains how to format an HTML document with CSS.

There are three ways of inserting a style sheel:
- External CSS (recommended)
- Internal CSS
- Inline CSS

Styles will be applied to elements by the following priority:
1. Inline style
2. External and internal style sheets (last read style will prevail)
3. Browser's default

## External CSS:
An external stylesheet is included into the HTML document using the `<link>` element. Such as:
`<link href="style.css" rel="stylesheet" type="text/css>`.

## Internal CSS
An internal style sheet is used to give a single HTML document a unique style.
The internal style is defined inside an `<style>` element, inside the head section.

## Inline CSS
An inline style is used to apply a unique style for a single element.
The style is added to the element using the style attribute.