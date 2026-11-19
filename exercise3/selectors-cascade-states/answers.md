# CSS selectors and which rule wins: my answers

## 1. When must you use a class selector, and not an element selector?
to select specific elements without affecting other elements with the same tag

## 2. What does the space mean in `.material-shelf p`?
it is the descendant selector, all `<p>` elements that are within the .material-shelf class will be selected regardless of layers

## 3. What does `>` mean in `.quick-nav > a`?
it is the child selector, only `<a>` elements that are directly one layer inside an element with the `.quick-nav` class will be selected

## 4. Why must a button link have a `:hover` style and a `:focus` style?
:hover lets the mouse users to know the button can be clicked when they move their cursor over it,<br>
:focus is more of accessibility, it lets the keyboard users to see which button is currently selected while navigating with "tab" key, and to know the button is ready to be used with "enter" key

## 5. If `a` and `.quick-nav > a` both set `color` on a navigation link, which selector wins in the stylesheet of this lesson?
.quick-nav > a , because element-with-class selectors has more priority than element-only selectors even if the element-with-class selectors is placed above element-only selectors, so if there is<br>
in the css: `a { color: yellow }` and  `.quick-nav > a { color: red }`<br>
`<div class=quick-nav><a>i am apple</a></div>` text color will be red and `<a>i am banana</a>` (outside of the .quick-nav class) text color will be yellow