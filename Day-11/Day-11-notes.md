# Web Development Day‑11

## 1. What is CSS?

1) CSS (Cascading Style Sheets) is a language used to control how HTML content looks — colors, fonts, spacing, layout, and responsiveness.  
2) CSS separates **content** (HTML) from **presentation** (design), making pages easier to maintain, reuse, and scale.  


## 2. Basic CSS rule syntax

1) A CSS rule targets one or more HTML elements and applies visual changes using properties and values.  
2) General pattern:  
   `selector { property: value; }`  
   Example:  
   `p { color: blue; font-size: 16px; }`  
   Here, `p` is the selector, `color` and `font-size` are properties, and `blue`, `16px` are their values.  


## 3. Ways to add CSS to HTML

1) **Inline CSS:** Add the `style` attribute directly on an HTML tag, e.g., `<p style="color: red;">Text</p>`. Good for quick tests, not for big projects.  
2) **Internal CSS:** Put rules inside a `<style>` tag in the `<head>` of an HTML file. Useful for small, single‑page demos.  
3) **External CSS:** Write styles in a separate `.css` file (e.g., `style.css`) and link it using `<link rel="stylesheet" href="style.css">` in the HTML `<head>`. This is the standard way for real projects.  


## 4. Core selector types

1) **Element (type) selector:** Targets all elements of a given tag.  
   Example: `p { line-height: 1.6; }` styles all `<p>` tags.  
2) **Class selector:** Targets elements with a specific `class` attribute.  
   Example:  
   CSS: `.highlight { background-color: yellow; }`  
   HTML: `<span class="highlight">Note</span>`  
3) **ID selector:** Targets a single element with a unique `id`.  
   Example:  
   CSS: `#main-title { font-size: 32px; }`  
   HTML: `<h1 id="main-title">Heading</h1>`  


## 5. First useful CSS properties

1) **Color and background:**  
   - `color`: text color, e.g., `color: #333;`  
   - `background-color`: element background, e.g., `background-color: #f5f5f5;`  
2) **Font and text:**  
   - `font-size`: text size, e.g., `font-size: 18px;`  
   - `font-family`: typeface, e.g., `font-family: Arial, sans-serif;`  
   - `text-align`: text alignment, e.g., `text-align: center;`  


## 6. Box model basics (just the idea)

1) Every visible HTML element behaves like a box with four parts: **content**, **padding**, **border**, and **margin**.  
2) For now, remember:  
   - `padding` = space inside the border, around the content  
   - `border` = the line around the element  
   - `margin` = space outside the border, separating this element from others  