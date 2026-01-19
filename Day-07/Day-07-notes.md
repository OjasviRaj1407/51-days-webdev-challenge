# Web Development Day‑07

## 1. Structuring a full registration form

1) Built a multi‑section **University Registration Form** with headings for Personal Details, Contact Information, Academic Information, Extracurricular Activities, and Account Creation.  
2) Used `<h1>`, `<h2>`, `<h3>`, `<p>`, and `<hr>` to visually separate sections so the form is easier to scan and fill.

## 2. Advanced input types and validation

1) Collected names with text inputs and used `placeholder` text (for example, `placeholder="e.g: ABC"`) to show example values.  
2) Used `<input type="date">` for DOB so the browser can show a date picker, and added `required` on key fields (first name, DOB, password) to prevent submission with missing critical information.  
3) Added `type="email"` and `type="tel"` for email and phone so the browser can help with basic format validation and mobile keyboards.

## 3. File upload, textarea, and dropdown select

1) `<input type="file">` lets the user upload a profile photo as part of the registration.  
2) `<textarea>` is used for Mailing Address to allow multi‑line input, with `rows` and `cols` controlling the visible size.  
3) `<select>` with multiple `<option>` elements (CSE, ECE, EEE, AE) provides a dropdown for choosing a course, which avoids typos and keeps the data consistent.

## 4. Grouping interests with checkboxes

1) The Extracurricular Activities section uses checkboxes (Sports, Music, Technology, Volunteering) so students can select **multiple** interests at once.  
2) All checkboxes share the same `name="interest"`, which allows the form to send multiple values for the same field when more than one activity is selected.

## 5. Account creation, submit, and reset buttons

1) The account section adds a required password field and a security answer to mimic real registration flows where login credentials are created at the end.  
2) A **Register** button (`<button type="submit">`) sends the form data to the server (once an action is defined), while a **Clear Form** button (`<button type="reset">`) resets all fields back to their initial values—useful during testing or when a user wants to start over.
