---
Title: "grid-gap"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Grids"
  - "Layout"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition

Specifies the spacing between grid elements within a grid framework.

## Syntax

```css
.div-container {
  grid-gap: <gap-value>;
}
```

where `<gap-value>` can be one of the following:

- Grid keyword: `normal`
- Pixel value: `3px`
- A percentage: `1%`

## Example 1

Columns with three pixels of spacing:

```css
.content-a-container {
  display: grid;
  grid-template:  150px 300px 150px / 1fr 1fr 1fr;
  grid-gap: 3px;
}
```

## Example 2

A one percent spacing across grid elements:

```css
.content-b-container {
  display: grid;
  grid-template: repeat(5, 19%) / auto 400px 400px auto;
  grid-gap: 1%;
}
```
