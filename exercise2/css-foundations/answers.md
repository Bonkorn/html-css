# CSS foundations: my answers

## 1. Which line in `index.html` connects the CSS file?
HERE in `<link rel="stylesheet" href="HERE">`

## 2. In `body { background-color: #ecfdf5; }`, what is the selector?
body in .css file selects `<body>` in .html file, and the background color will changed to #ecfdf5

## 3. In that same rule, what is the property and what is the value?
property is background-color, value is #ecfdf5

## 4. Why does `.resource-card` start with a dot in CSS?
if there is `class="resource-card"` in html, in the css, use `.resource-card` (after dot, then the exact same name as the class in the html) to select the elements that are within this class

## 5. What is the difference between padding and margin in the resource card?
padding is the spacing inside border, margin is the spacing outside border

## 6. Which selector, property and value did you change in "Make one small change", and what changed on the page?
`body{ background-color: skyblue;}`, and page background color changed to skyblue<br>
`h1 { color: magenta; }`, and h1 text color changed to magenta<br>
`h2 { color: deeppink; }`, and h2 text color changed to deeppink<br>
`.resource-card { padding: 48px; }`, and from originally 24px to 48px, the spacing inside the border became wider<br>
`th { background-color: #fbafaf; }`, and the table header background color changed to #fbafaf (light red)