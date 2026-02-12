# HTML Tables

This section covers HTML attributes, classes, and Ids

## What Problem Does This Solve?

In the case when one needs to display stats of any kind, tables are great for displaying this data into a table format.

## Definition

Attributes modify the behavior of an element and classes and ids are attributes that let us style certain elements and/or hook up that element to JavaScript in order to do something dynamic.

## Mental Model

## Syntax/Structure

```html
<!-- This anchor element has an href attribute which sends the user to the location of the link -->
<a href="https://developer.mozilla.org/en-US/">MDN Web Docs</a>

<!-- classes let you denote what type of something is to you (ex. what type of h2 is this) -->
<h2 class="article-title">This is my secondary heading</h2>
<p class="article-text">This paragraph describes the article...</p>

<!-- These classes are reusable, which make it easy to apply the same styling to multiple elements -->
<style>
  .article-title,
  .article-text {
    font-weight: bold;
  }

  .article-title {
    color: red;
  }

  .article-text {
    color: black;
  }
</style>

<!-- Ids are unique, you cannot repeat Id names -->
<h1 id="brand-name"></h1>
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
