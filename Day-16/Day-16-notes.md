# Web Development Day‑16 – Color in CSS

## 1. Why color in CSS matters

1) Every color on a screen is created by mixing light from three channels: **Red, Green, and Blue (RGB)**. Each pixel is tiny red, green, and blue sub‑pixels at different intensities.  
2) As developers, we need a precise way to tell the browser the “recipe” for how much red, green, and blue light to mix, so CSS defines several color formats to express that recipe.

## 2. Color keywords (named colors)

1) CSS includes a set of predefined **color keywords** like `red`, `blue`, `green`, `black`, `white`, `lightblue`, `darkslategray`, etc.  
2) These are human‑friendly and great for quick styling or prototypes, but the list is limited (around 140 names), so they are not enough when you need precise brand or UI colors.

```css
h1 {
  color: red;
}

p {
  color: darkslategray;
}

body {
  background-color: lightblue;
}



## 2. Hexadecimal colors

/* Pure red, green, blue, black, white, and some grays */
.red-box {
  background-color: #FF0000;
}

.page-bg {
  background-color: #FFFFFF; /* white */
}

.text-muted {
  color: #333333;            /* dark gray */
}

.hero-section {
  background-color: #E0B0FF; /* lavender-like shade */
}




## 3. RGB and RGBA functions

/* Solid colors with rgb() */
button.primary {
  background-color: rgb(0, 123, 255);
}

/* Semi‑transparent overlay */
.overlay {
  background-color: rgba(0, 0, 0, 0.5); /* 50% transparent black */
}

.alert {
  background-color: rgba(255, 0, 0, 0.2); /* light transparent red */
}



## 4. HSL and HSLA (Hue, Saturation, Lightness)

/* Base red and variations */
.base-red {
  color: hsl(0, 100%, 50%);   /* pure, vivid red */
}

.dark-red {
  color: hsl(0, 100%, 25%);   /* darker red */
}

.desaturated-red {
  color: hsl(0, 50%, 50%);    /* faded red */
}

/* Semi-transparent blue */
.glass-card {
  background-color: hsla(240, 100%, 50%, 0.5);
}
