# Block vs Inline Elements

## About

This folder covers the difference between HTML block-level and inline elements, which is fundamental to understanding layout and styling.

## Files

- **index.html** - Demonstrates block vs inline element behavior

## Content

### Block-Level Elements
- Take full width available
- Start on a new line
- Stack vertically
- Examples: `<p>`, `<div>`, `<h1>` to `<h6>`, `<ul>`, `<ol>`

### Inline Elements
- Take only as much width as needed
- Flow within content
- Do not start on new line
- Examples: `<a>`, `<span>`, `<strong>`, `<em>`, `<img>`

## Key Differences

| Property | Block Elements | Inline Elements |
|----------|----------------|-----------------|
| Width | Full width | Content width |
| New line | Yes | No |
| Margins/Padding | All sides work | Only horizontal work |
| Can contain | Block or inline | Text/inline only |

## Note

With CSS `display` property, elements can be changed from block to inline and vice versa.
