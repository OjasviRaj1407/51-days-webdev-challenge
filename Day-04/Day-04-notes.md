# Web Development Day‑04

1) A **file path** tells the browser where to find another file (HTML, image, CSS, etc.) relative to the current page. [web:193]  
2) There are two main types in HTML:
   - **Relative file path** – starts from the current file’s location.
   - **Absolute file path** – full URL that includes `http://` or `https://`. [web:180][web:190]

## 2. Relative file paths

1) Relative paths are used for **your own project files** and change depending on where the current HTML file lives. [web:193]  
2) Same folder:  
   - Problem: `index.html` needs to link to `about.html`.  
   - Syntax: `href="about.html"` (just the filename, because both are neighbors in the same folder). [web:193]  
3) Sub‑folder (going **down**):  
   - Problem: `index.html` needs an image from `images/logo.png`.  
   - Syntax: `src="images/logo.png"` – folder name + `/` + filename. [web:193]  
4) Parent folder (going **up**):  
   - Problem: `pages/contact.html` wants an image from `images/logo.png` sitting one level above.  
   - Syntax: `src="../images/logo.png"` – `../` moves up one folder, then you go down into `images/`. [web:193]

## 3. Absolute file paths

1) Absolute paths are full URLs that start with `http://` or `https://`, usually pointing to **other websites’ files**. [web:180][web:190]  
2) Example:  
   - `src="https://www.example.com/images/logo.png"`  
   - This will work from any page, because it does not depend on your project’s folder structure.  
3) Using a local system path like `C:/Users/OR/Desktop/my-website/images/logo.png` is a mistake; it only works on that one computer and breaks once the site is deployed to a server. [web:193]

## 4. Why relative paths are safer

1) Relative paths can only access files inside your project folder and its sub‑folders, so the browser cannot reach private files elsewhere on your machine. [web:193][web:191]  
2) When you move the project to another system or server, relative paths still work as long as the folder structure is the same, which makes projects more portable and secure. [web:193]

## 5. Quick rules of thumb

1) For **internal project links** (your own HTML, CSS, images): always use **relative paths** like `about.html`, `images/logo.png`, `../styles/main.css`. [web:193]  
2) For **external resources** (CDNs, other websites): use **absolute URLs** like `https://cdn.example.com/library.js`. [web:180][web:190]  
3) Remember:
   - Same folder → `filename.ext`  
   - Go down into a folder → `folder/filename.ext`  
   - Go up one level → `../folder/filename.ext`
