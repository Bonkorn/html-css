# The box model: my answers

## 1. Which element is the parent panel?
`<article class="activity-panel">`

## 2. Which CSS rule controls the space inside the panel border?
padding controls the space inside the border

## 3. Which CSS rule controls the space after each panel?
margin controls the space outside the border

## 4. Why does the image use `<width: 100%>`?
width: 100% sets the image's width to match 100% of the width of its parent container  (e.g  the panel element, `<article class="panel-image">`), so the image will stretch or shrink horizontally when it fills the container

## 5. Why can both panels use the same CSS?
because if there is multiple named class="item" in the html, one .item in the css can still match the multiple same named parent elements