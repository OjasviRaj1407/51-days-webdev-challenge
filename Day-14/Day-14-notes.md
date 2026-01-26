# Web Development Day‑14 – External CSS (Gym Website)

## 1. What is external CSS?

1) External CSS means writing all your styles in a separate `.css` file (for example, `Day-14-code2.css`) instead of inside the HTML file.  
2) The HTML file then **links** to that CSS file, so the browser can apply those styles when it renders the page.


## 2. How we linked the external CSS in this file

## 3. In the `<head>` section, the external stylesheet is linked using the `<link>` tag:  
   ```html
   <link rel="stylesheet" href="./Day-14-code2.css">


rel="stylesheet" tells the browser that this link is a stylesheet, and href="./Day-14-code2.css" is the path to the CSS file stored in the same folder as the HTML file.


## 4. CSS rules in the external file

The Day-14-code2.css file contains the styling rules for headings:

css
h1{
    background-color: pink;
}

h2{
    background-color: aquamarine;
}
These rules automatically style all <h1> and <h2> elements in the linked HTML page, such as the “Gym Website” heading and the “Exercise” and “Diet” sub‑headings.

## 5. Why external CSS is better than inline/internal for projects

Separation of concerns : HTML focuses on structure and content (headings, lists, text), while CSS in a separate file controls the design. This keeps both files cleaner and easier to read.

Reusability and consistency : The same CSS file can be linked to multiple HTML pages, so you get a consistent look across the whole site and can change styles in one place.