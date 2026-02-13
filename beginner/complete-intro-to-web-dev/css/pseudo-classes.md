# CSS Pseudo-classes

This section covers the CSS cascade and how the browser determines what styles get applied to an element when multiple rules are applied to it.

## What Problem Does This Solve?

Pseudo classes enable dynamic styling of content without altering the HTML markup.

## Definition

Pseudo classes allow us to apply styles conditionally based on the current state of an interactive element, typically used for buttons and links.

## Mental Model

## Syntax/Structure

Pseudo-classes can be categorized based on their functionality:

**User Action: apply style based on user interactions**

- :hover → styles an element when the user's pointer moves over it (does not work on tablet/mobile devices)

```css
button {
  background-color: transparent;
}

button:hover {
  background-color: black;
}
```

- :focus → styles an element when it receives focus via clicking or tabbing with the keyboard

```css
a {
  border: none;
}

a:focus {
  border: 1px solid blue;
}
```

**Structural: selects elements based on their position within the document structure**

- :first-child → selects the first child of its parent

```html
<ul>
  <li class="nav-list"></li>
  <li class="nav-list"></li>
  <li class="nav-list"></li>
</ul>
```

```css
/* This will style the first li element with the class 'nav-list' */
.nav-list:first-child {
  color: limegreen;
}
```

## When to Use

Avoid the cascade, its a tool to be used sparingly.

## Interview Explanation

## Related Concepts
