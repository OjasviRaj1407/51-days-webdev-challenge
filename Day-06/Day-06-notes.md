# Web Development Day‑06

## 1. Forms and the `<form>` tag

1) A form is used to collect user input that can later be sent to a server (for example, sign‑up, login, surveys).  
2) The `<form>` tag wraps all form controls (inputs, labels, buttons). In real projects it usually has attributes like `action` (where to send data) and `method` (`GET` or `POST`).

## 2. Text, number, and password inputs

1) `<input type="text">` creates a single‑line text box (used here for Name and Father’s Name).  
2) `<input type="number">` restricts the field to numeric values, which is suitable for Age.  
3) `<input type="password">` masks the characters as the user types, keeping the password hidden on screen.

## 3. Labels, id, name, and the label–input link

1) `<label>` provides a human‑readable title for an input, improving usability and accessibility.  
2) The `for` on the label must match the `id` on the input (for example, `for="name"` with `id="name"`), so clicking the label focuses or toggles that specific input.  
3) The `name` attribute (like `name="userName"`) is the key used when the form is submitted; the server receives key–value pairs such as `userName=Ojasvi`.

## 4. Radio buttons for single choice

1) `<input type="radio">` creates a radio button; it is used when the user must choose exactly one option from a set (for example, Male, Female, Other).  
2) All gender radio buttons share the same `name="gender"`, which groups them so only one can be selected at a time. The `value` attribute (`"male"`, `"female"`, `"other"`) is what gets submitted.

## 5. Checkboxes for multiple selections

1) `<input type="checkbox">` allows independent on/off choices; multiple checkboxes can be selected together (like C++, Java, Python, JavaScript subjects).  
2) Using the same `name="subject"` for all subject checkboxes sends multiple values for the same key when more than one option is checked. The `value` attribute tells the server which subject was chosen.

## 6. Submit button and basic layout

1) `<input type="submit">` creates a button that triggers form submission to the URL set in the `action` attribute (or reloads the page if no action is given).  
2) `<br><br>` is used here to add line breaks between fields for quick layout. In real projects, spacing is usually handled with CSS margins or flexbox/grid instead of repeated `<br>` tags.
