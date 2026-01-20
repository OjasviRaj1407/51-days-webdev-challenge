# Web Development Day‑08

## 1. Semantic layout tags

1) Instead of only using `<div>`, this page uses semantic tags like `<header>`, `<main>`, `<section>`, and `<footer>` to describe the structure.  
2) Semantic tags make HTML easier to read, help screen readers understand the layout, and give better meaning to each block (for example, header vs content vs footer).

## 2. Grouping content with `<section>`

1) Each logical part of the profile (Personal Details, Contact Information, Academic Information, Extracurricular Activities) is wrapped in its own `<section>`.  
2) Using sections with proper headings (`<h3>`, `<h4>`) makes the page scannable and sets you up for good document outline and accessibility.

## 3. Reusing registration data as read‑only view

1) The profile page is a **read‑only summary** of data that could have been collected from the registration form on Day‑07 (name, DOB, gender, email, course, activities).  
2) Practicing both forms (for input) and profile pages (for display) builds the mental model of how front‑ends often work: collect data in one screen, then show it in another.

## 4. Using tables for compact structured info

1) The “Academic Information” section uses a small table with two columns (“Field” and “Value”) to show course, year/semester, and registration ID.  
2) Tables work well when you have label–value pairs that should line up nicely, instead of multiple separate paragraphs.

## 5. Lists and the `<strong>` tag

1) An unordered list `<ul>` is used to show extracurricular activities like Sports, Music, Technology, and Volunteering so that each activity is a separate, clear list item.  
2) The `<strong>` tag is used inside paragraphs (for example, `<strong>First Name:</strong> ABC`) to visually bold labels and also give them semantic emphasis, which helps both readability and screen readers.

## 6. Footer as a meta note

1) The `<footer>` element holds a short line explaining that this is a practice profile generated from registration data.  
2) Footers are ideal for meta information: copyright notices, “about this page” notes, or links to related resources.
