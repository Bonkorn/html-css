# Image positioning: my answers

## 1. When must an image go in the HTML, with `<img>`?
an image belongs in html use `<img>` when its part of the page content, like a photo or a screenshot that help explain the page easily, and if the image fails to load or those using screen reader, the text in the alt attribute will be loaded instead

## 2. When must an image go in the CSS, with `background-image`?
an image goes in the background-image for decorative purposes, acting as background behind the image, the page content can still make sense even without this background decoration, for example: a background-image of trees & sky can be put behind an image of plants & flowers, a background-image of road or garage can be put behind an image of car or motorcycle

## 3. What does `object-fit: cover` do?
it forces the image to fill in a fixed-size container, while maintaining the image's aspect ratio, so the image don't look stretched or shrinked

## 4. Why does `.photo-panel` need `position: relative`?
the parent use position: relative, so it sets the boundary for its child labels where they use position: absolute, so they position themselves into its parent boundary, if position: relative is removed from the parent, the label will position itself into different parents, if the label cannot find a parent, it will position itself to the page

## 5. What makes the text easy to read on top of the background image?
text on top of the background image directly is diffcult to read, the way to make it easy to read is put the text in a panel with its own background color, light color like full white, with rgb 255,255,255, will make it easy to read

## 6. Which change did you make? What changed in the browser, and which CSS property caused it?
i changed the height of .feature-photo from 340px to 280px, and the image became shorter vertically, the css property caused it, is height 