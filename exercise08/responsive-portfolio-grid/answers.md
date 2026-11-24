# Responsive portfolio grid: my answers

## 1. Which element became the grid container?
`<section class="project-grid" aria-label="Portfolio project list">`

## 2. Which elements became the grid items?
`<article class="project-card">`

## 3. Which rule makes the columns for wide screens?
`.project-grid { grid-template-columns: repeat(4, 1fr);}`

## 4. Which rule changes the layout for a browser window of medium width?
`@media (max-width: 820px) { .project-grid { grid-template-columns: repeat(2, 1fr); } }` 

## 5. Which rule stops the featured card from making the phone layout too wide?
`@media (max-width: 560px) { .project-card.featured { grid-column: auto; } }`