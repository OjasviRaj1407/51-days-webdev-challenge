# Web Development Day‑05

## 1. HTML boilerplate

1) An HTML boilerplate is the standard starter template every page uses so the browser understands the document correctly.  
2) It always begins with `<!DOCTYPE html>` (tells the browser to use modern HTML5), followed by `<html>`, a `<head>` section for metadata, and a `<body>` section for visible content.  
3) Common `<head>` tags include:
   - `<meta charset="UTF-8">` for proper character encoding.  
   - `<meta name="viewport" content="width=device-width, initial-scale=1.0">` for responsive layouts.  
   - `<title>...</title>` for the browser tab text.  

## 2. The `<div>` element (generic box)

1) `<div>` is a generic container for grouping other elements; by itself it has no semantic meaning or special behavior.  
2) Developers wrap related content inside a `<div>` so it can be moved, styled, or positioned together using CSS (for example, putting a whole navbar, card, or section inside one div).  
3) Because `<div>` is non‑semantic, it is better to use semantic tags like `<header>`, `<main>`, `<section>`, `<article>`, and `<footer>` when a clear meaning exists, and reserve `<div>` for generic layout/grouping needs.  

## 3. Class and id attributes (labels for the box)

1) `id` is a unique label for a single element on the page, while `class` is a reusable label that can be applied to many elements.  
2) In CSS:
   - `#first { ... }` selects the element with `id="first"`.  
   - `.second { ... }` selects all elements with `class="second"`.  
3) Typical use:
   - Use an id for one‑of‑a‑kind elements (e.g., main header, specific section targeted by JavaScript).  
   - Use classes for styling groups of elements that share the same look (buttons, cards, text blocks).  
4) IDs have higher specificity than classes in CSS, so if both target the same element, the id‑based rule will override the class rule.