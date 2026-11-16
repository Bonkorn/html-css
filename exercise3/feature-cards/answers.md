# Style feature cards with selectors: my answers

## 1. Which selector styles the full page or the page background?
body

## 2. Which selector styles the design that all cards use?
features , resources

## 3. Which selector styles an element inside a section or a card?
card-grid , feature-card

## 4. Which selector uses `>`?
site-nav>a , features>p

## 5. Which selector changes the page on hover?
.site-nav>a:hover , .button-link:hover

## 6. Which selector changes the page on focus?
.site-nav>a:focus , .button-link:focus

## 7. Which two rules set the same property on one element, and which rule wins? Give the selectors, the property, the value that shows, and the reason.
`.site-nav { background-color: green; }`
<br>and<br>
`.site-nav>a:hover,
.site-nav>a:focus {
  background-color: yellow;
}`<br>
by default, the background color in the class site-nav is green, if cursor hover or clicked on it, it will be yellow