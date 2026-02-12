# HTML Tags

This section covers some of the most commonly used tags in HTML. Each converts random text, into a meaningful part of a document. HTML is not a programming language, it needs JavaScript to actually do something.

## What Problem Does This Solve?

HTML lets us structure the content of webpages to be meaningful and accessible. We do this using tags.

## Definition

The basic building block of an HTML document is the tag. A tag desicribes the content inside of it by using a closing an opening tag.

## Mental Model

## Syntax/Structure

- Headings (h1-h6): h1 is treated as the main heading, other low-ranking headings signify subheadings and sections.

**Code**

```html
<h1>This is my main heading</h1>
<!-- Some content -->

<h2>Subheading</h2>
<!-- Some content related to the subheading -->
```

- Paragraphs (p): puts a paragraph of text together

**Code**

```html
<p>This is a paragraph of text</p>
<p>This is another paragraph of text</p>
```

- Anchor (a): a link to somewhere else. Every tag needs a destination of where the link should take you using an href attribute.

**code**

```html
<!-- A link that goes to Frontend Masters -->
<a href="https://frontendmasters.com">Frontend Masters</a>
```

- div (div): Short for division, acts like a cardboard box.

**Code**

```html
<!-- An empty div -->
<div></div>

<!-- A div with meaning inside of it, typically used as a generic divider -->
<div>
  <h1>This is my main heading</h1>
  <p>This paragraph describes my heading.</p>
</div>
```

- Span (span): a container for a small piece of text. It distinguishes a part of text to be targeted later with CSS and JavaScript.

**Code**

```html
<!-- Using a CSS selector, the text "span" could be styled differently than the text around it -->
<p>This paragraph contains a <span class="color-accent">span</span> element</p>
```

- Lists and list items (ul, ol, li): lists can be unordered (order doesn't matter) or ordered (order matters) and each list is made up of list items.

**Code**

```html
<ol>
  <li>Item One</li>
  <li>Item Two</li>
  <li>Item Three</li>
</ol>

<ul>
  <li>Item</li>
  <li>Another item</li>
  <li>And another item</li>
</ul>
```

- Button (button): can be used by JavaScript to respond to a user clicking it. It is useful for submitting form data. 

**Code**
```html 
<button>Click me</button>
```

- Image (img): loads images onto the page. If the image is part of the content it should be included in the HTML, if the image is used for styling purposes (like a background image) then include it in the CSS
  - img tags are VOID elements (self-closing)

**Code**
```html
<img
  src="url.com"
  alt="descriptive text about the image for web crawlers and assistive technologies"
>
```

## Example

**Code**

```html
<button>Click me</button>
```

**Result**
<button>Click me</button>

## Common Mistakes

## When to Use

## Interview Explanation

## Related Concepts
