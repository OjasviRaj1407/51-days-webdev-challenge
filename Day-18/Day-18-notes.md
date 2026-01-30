# Web Development Day‑18 – CSS Box Model

## 1. What is the CSS box model?

1) In CSS, every visible element is treated as a **box** made of four layers: content, padding, border, and margin.  
2) Understanding how these layers interact is essential for controlling spacing, alignment, and layout in any webpage.


## 2. The four parts of the box

1) **Content :** The actual stuff inside the element – text, images, or other elements.  
2) **Padding :** Space between the content and the border. It pushes the content inward and increases the box’s inner size.  
3) **Border :** The line surrounding the padding and content. It has width, style, and color.  
4) **Margin :** Space outside the border, separating this box from other elements around it.


## 3. Key properties in the box model

1) `padding`: Controls inner spacing (can be one value or up to four: top, right, bottom, left).  
   - Examples : `padding: 16px;`, `padding: 8px 12px;`  
2) `border`: Controls the frame around the element.  
   - Example : `border: 2px solid #d1d5db;`  
3) `margin`: Controls outer spacing between this element and others.  
   - Examples : `margin: 0 auto;`, `margin-bottom: 20px;`  


## 4. box-sizing: border-box

1) By default, width and height apply only to the content box, and padding + border are added on top (`box-sizing: content-box;`).  
2) Setting `box-sizing: border-box;` makes the declared width/height include content + padding + border, which simplifies layout math and is common in modern CSS.

```css
* {
  box-sizing: border-box;
}