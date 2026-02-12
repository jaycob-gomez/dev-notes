# HTML Inputs

This section covers HTML input elements and how they are used to collect user information.

## What Problem Does This Solve?

HTML inputs let users log in/sign up to a service online, post comments on websites, and send data over the internet. Inputs collect user data and then JavaScript takes that data and does something meaningful with it.

## Definition

Input tags are void elements that gather user data. The type of data they accept from the user is determined by the attribute specified within the tag.

## Mental Model

## Syntax/Structure

```html
<!-- Default type of text -->
<input />

<!-- Accepts color input -->
<input type="color" />

<!-- Converts the input into a checkbox -->
<input type="checkbox" />

<!-- Textareas are for multi-line input -->
<textarea></textarea>

<!-- Selects lets users select from a dropdown of options -->
<select>
  <option value="los-angeles">Los Angeles</option>
  <option value="seattle">Seattle</option>
  <option value="las-vegas">Las Vegas</option>
</select>

<!-- The form element groups related inputs, textareas, and selects -->
<form>
  <input placeholder="First Name" />
  <input placeholder="Last Name" />
</form>
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
