# Style feature cards with selectors: my answers

## 1. Which selector styles the full page or the page background?
body

## 2. Which selector styles the design that all cards use?
.feature-card

## 3. Which selector styles an element inside a section or a card?
.features p , .feature-card h3 , .resources a , .feature-card p , .tools a

## 4. Which selector uses `>`?
.site-nav>a , .features>p

## 5. Which selector changes the page on hover?
.site-nav>a:hover , .button-link:hover

## 6. Which selector changes the page on focus?
.site-nav>a:focus , .button-link:focus

## 7. Which two rules set the same property on one element, and which rule wins? Give the selectors, the property, the value that shows, and the reason.
on line 13, `.feature-card { background-color: #ae50e4; }`,<br>
on line 75, `.feature-card { background-color: #a9e3e7; }`,<br>
the rule on line 75 wins because both rules use the same selector (equal specificity), but the rule that comes later will override the earlier ones, in this case, elements that use the class="feature-card" will use #a9e3e7 as its background color