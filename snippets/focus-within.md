---
title: Focus Within
tags: visual,interactivity,intermediate
---

Changes the appearance of a form if any of its children are focused.

```html
<div class="focus-within">
  <form>
    <label for="given_name">Given Name:</label> <input id="given_name" type="text" /> <br />
    <label for="family_name">Family Name:</label> <input id="family_name" type="text" />
  </form>
</div>
```

```css
form {
  border: 3px solid #2d98da;
  color: #000000;
  padding: 4px;
}

form:focus-within {
  background: #f7b731;
  color: #000000;
}
```

#### Explanation

- The psuedo class `:focus-within` applies styles to a parent element if any child element gets focused. For example, an `input` element inside a `form` element.

#### Browser support

<span class="snippet__support-note">⚠️ Not supported in IE11 or the current version of Edge.</span>

- https://caniuse.com/#feat=css-focus-within
