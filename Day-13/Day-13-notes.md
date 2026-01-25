# Web Development Day‑13 – Inline CSS

## 1. Recap: Inline vs Internal CSS in this file
1) In the current gym page, the `<style>` block inside the `<head>` is internal CSS, because it defines styles for all `<h1>` and `<h2>` elements on the page at once.  
2) Inline CSS would go directly on individual elements using the `style` attribute, for example: `<h1 style="background-color: blue;">Gym Website</h1>`.

## 2. How inline CSS would look in the gym page
1) Current internal CSS in the file:
```html
<style>
    h1{
        background-color: blue;
    }

    h2{
        background-color: antiquewhite;
    }
</style>

## 3. Inline CSS version of the same idea:

<h1 style="background-color: blue;">Gym Website</h1>

<h2 style="background-color: antiquewhite;">Exercise</h2>

<h2 style="background-color: antiquewhite;">Diet</h2>

## 4. Where inline CSS becomes a problem
If you use inline CSS everywhere and later want to change all <h2> backgrounds, you must edit every <h2> tag manually, which is slow and may lead to inconsistent styles.

Internal or external CSS lets you change the style in one place (the rule for h2) and automatically update all headings, which is much easier to maintain for bigger pages or projects.