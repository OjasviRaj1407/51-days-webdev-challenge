# Web Development Day‑10

## 1. Goal for the day

1) Today’s focus is a theory-heavy topic that does not require any image, audio, or video files.  
2) The practice page revises **HTML lists** and introduces the idea of **block vs inline elements** using only text content.

## 2. Unordered and ordered lists

1) An unordered list uses `<ul>` (unordered list) with `<li>` (list item) tags and typically displays bullet points. It is useful when the order of items does not matter.  
2) An ordered list uses `<ol>` with `<li>` items and shows them with numbers or letters, which is helpful when sequence or priority is important (steps, rankings, instructions).

## 3. Description lists

1) A description list uses `<dl>` (description list), with `<dt>` for the term and `<dd>` for its description.  
2) Description lists work well for glossaries, FAQs, or any situation where you want a word followed by an explanation instead of a simple bullet.

## 4. Block-level elements

1) Block-level elements (like `<div>`, `<p>`, `<h1>`–`<h6>`, `<section>`) always start on a **new line** and typically take up the full available width of their parent container.  
2) Browsers automatically add space above and below block elements, so they naturally stack vertically and form the main structure of the page.

## 5. Inline elements

1) Inline elements (like `<span>`, `<a>`, `<strong>`, `<em>`) do **not** start on a new line; they flow inside a block of text and only take up as much width as their content.  
2) Inline elements are ideal for styling or marking up small pieces of text inside a paragraph without breaking the line (for example, highlighting a word or turning it into a link).

## 6. Putting it together in the practice file

1) The Day‑10 practice page uses `<ul>`, `<ol>`, and `<dl>` to summarize topics learned so far and to define basic HTML terms in one place.  
2) The same page demonstrates block vs inline behavior by stacking paragraphs (block elements) and placing several `<span>` elements on the same line inside a single paragraph (inline elements), giving a clear visual difference in the browser.
