# CSS Box Model

This section covers the CSS Box Model and how we can use it to move elements around.

## What Problem Does This Solve?
Since the browser displays everything as a box

## Definition

The box model is the browser's way of displaying content on the user's device. It does this by representing each element as a rectangular box containing the content, padding, border, and margin.

## Mental Model

```
+---------------------------+
|        margin             |
|  +---------------------+  |
|  |      border         |  |
|  |  +---------------+  |  |
|  |  |   padding     |  |  |
|  |  |  +---------+  |  |  |
|  |  |  | content |  |  |  |
|  |  |  +---------+  |  |  |
|  |  +---------------+  |  |
|  +---------------------+  |
+---------------------------+
```

Think of each element like a package being shipped.

- Content → item inside the box
- Padding → bubble wrap
- Border → cardboard box
- Margin → empty space between packages

## Syntax/Structure

**Display**

- Everything in CSS has a display property whether it is explicitly set or not.
- Ex. every div is block by default and every span is inline by default
- Values include: block | inline | inline-block | flex | grid

## When to Use

**Use padding when:**
You want space inside the element.

Ex:

- Button text not touching edges
- Card content breathing room
- Clickable area larger

**Use margin when:**
You want space between elements.

Ex:

- Distance between sections
- Spacing between cards
- Layout gap

**Use border when:**
You want visible boundaries or outlines.

Ex:

- Debugging layout
- Card outlines
- Buttons

## Interview Explanation

The browser's rendering engine represents each element as a rectangular box that we can use CSS to manipulate each box. The browser lays out your page by calculating: how big is each box, and how much space does it take?

## Related Concepts
