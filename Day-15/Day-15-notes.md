# Web Development Day‑15 – Element, Class, ID & Grouping Selectors

## 1. Element (Tag) Selector

1) An **element selector** targets every HTML element of a specific tag on the page (for example, all `<p>` tags or all `<h2>` tags).  
2) Syntax: just the tag name (without `< >`) followed by a rule block:  
   ```css
   p {
     color: #333333;
     line-height: 1.6;
   }

## 2. Class Selector

1) A class selector targets all elements that have a particular class attribute, and it starts with a dot . in CSS.

2) Classes are reusable: you can apply the same class to many different tags (like <p>, <div>, <h3>) to give them a shared style.

```css
.warning-text {
  color: red;
  font-weight: bold;
}

.highlight {
  background-color: yellow;
}

## 3. ID Selector

1) An ID selector targets exactly one element with a specific `id` value and starts with `#` in CSS.  
2) IDs must be unique per page, so they’re best for single, major sections like headers, footers, or main layout areas.  

```css
#main-header {
  background-color: #f8f9fa;
  border-bottom: 1px solid #dee2e6;
  padding: 20px;
}


## 4. Grouping Selector

1) A grouping selector lets you apply the same declarations to multiple selectors at once by separating them with commas.

2) This keeps your CSS DRY (Don’t Repeat Yourself) and easier to maintain.

```css
/* DRY version */
h1, h2, h3 {
  font-family: 'Arial', sans-serif;
  color: navy;
}
This single rule replaces three separate, repetitive rules for h1, h2, and h3.

