# CSS selectors and which rule wins: my answers

## 1. When must you use a class selector, and not an element selector?
to select specific elements without affecting other elements with the same tag

## 2. What does the space mean in `.material-shelf p`?
descendant selector, elements within the class will be selected regardless of layers

## 3. What does `>` mean in `.quick-nav > a`?
child selector, only elements within the same layer as the class will be selected

## 4. Why must a button link have a `:hover` style and a `:focus` style?
:hover is when cursor hover on the button but not clicked, it will use the `:hover` style,<br>
:focus is when the button is clicked, it will use the `:focus` style

## 5. If `a` and `.quick-nav > a` both set `color` on a navigation link, which selector wins in the stylesheet of this lesson?
`.quick-nav > a` will win because it is more specific

# Style feature cards with selectors: my answers

## 1. Which selector styles the full page or the page background?
body

## 2. Which selector styles the design that all cards use?
.material-card

## 3. Which selector styles an element inside a section or a card?
.material-shelf

## 4. Which selector uses `>`?
child selector

## 5. Which selector changes the page on hover?
:hover

## 6. Which selector changes the page on focus?
:focus

## 7. Which two rules set the same property on one element, and which rule wins? Give the selectors, the property, the value that shows, and the reason.
if there is `.item { background-color: blue }` and `.item p { background-color: red }`, the background color of entire `class="item"` will be blue, but except the paragraphs will be red