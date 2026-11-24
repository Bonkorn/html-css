# CSS Grid and media queries: my answers

## 1. Which element is the grid container on this page?
`<section class="resource-grid" aria-label="Learning resources">`

## 2. Which elements are the grid items?
`<article class="resource-card">`

## 3. What does `1fr` mean in this grid?
1fr splits the grid container's available space, so each column will have the equal width

## 4. Why does the highlighted card need a reset in the phone media query?
without a grid-column reset, the highlighted card will display a very wide column, making the reading less efficient as phone readers need to scroll horizontally

## 5. Why must you test the same page at more than one width of the browser window?
testing with different viewports like computer, phone, tablet to ensure readers with different devices can read the page easily

## 6. Which change did you make? What changed in the browser, and which CSS property or media query caused it?
`.resource-grid { grid-template-columns: repeat(2, 1fr); }`, each row had 3 columns, now it becomes 2 columns