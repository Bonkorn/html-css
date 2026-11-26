# Bootstrap foundations: my answers

## 1. What does Bootstrap do when your HTML uses `class="btn btn-primary"`?
the browser reads 2 classes separately, btn sets the button structure like its shape, spacing, btn-primary sets the button styling like text and background colors

## 2. Why does this lesson load Bootstrap before `custom.css`?
because css rules are loaded from top to bottom, if custom.css is placed below bootstrap, the rules in bootstrap same as the ones in custom.css will be overridden by custom.css

## 3. What are the three main layers in the nesting pattern of the Bootstrap grid?
container, row, col

## 4. Which two navbar values must be the same, so that the collapsing menu works?
data-bs-target="#lessonMenu" and id="lessonMenu" must match so bootstrap knows which menu to open/close

## 5. Which parts of the pattern lab come from Bootstrap, and which parts come from `custom.css`?
bootstrap provides the structure like grid, cards, buttons, etc; custom.css provides the styling like background & text colors, borders, etc