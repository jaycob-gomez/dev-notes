# CSS Cascade

This section covers the CSS cascade and how the browser determines what styles get applied to an element when multiple rules are applied to it.

## What Problem Does This Solve?

## Definition

The basic building block of CSS is the rule. A rule is the set of instructions that tells the browser how an HTML element should look

## Mental Model

## Syntax/Structure

**When 2 rules have the same specificity the one that is declared last will prevail**

```css
.title {
  color: red;
}

.title {
  color: green; /* This will override the red color */
}
```

**2 classes vs 1 Class**

```css
.main-brand-3.title-3 {
  color: red;
}

.title-3 {
  color: green;
}

/* The element will end up being red because the first rule is more specific */
```

**Classes vs tags**

```css
.main-title {
  color: orange;
}

h1 {
  color: green;
}

/* If the h1 is given the class 'main-title' the class rule will apply since class selectors are more specific than type selectors */
```

**IDs**
Use IDs sparingly as they can be a wrecking ball in your CSS. No matter how many class selectors you write for an element, 1 ID selector will always be more specific and the ID selector rules will get applied.

```css
/* This style will get applied over the ridiculous selector below - NEVER write CSS like that as it makes code more difficult to maintain */
#site-brand {
  color: red;
}

h1.nav-head.nav-main.main-heading.site-title {
  color: green;
}
```

**!important**
Never use this as it is even more specific than the id selector

```css
h1 {
  color: yellow !important;
}
```

## When to Use
Avoid the cascade, its a tool to be used sparingly.
## Interview Explanation

## Related Concepts
