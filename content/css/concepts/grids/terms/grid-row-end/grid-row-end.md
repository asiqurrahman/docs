---
Title: "grid-row-end"
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

Specifies the end of a content span over a set of rows within a grid framework.

## Syntax

The grid is a combination of horizontal and vertical lines that frame the rows and columns, which are the spaces between the lines. The top left corner of a grid is defined by a vertical and horizontal line, each designated the value 1. The right side of the first column and the underside of the first row are defined by lines with the value 2, and so on through value n. 

```css
.some-text {
  grid-row-end: <grid-value>;
}
```

where `<grid-value>` can be one of the following:

- Grid keyword: `auto`
- Grid line value: `1`
- Grid line name: `article-content-start`

## Example 1

Content that starts on the second row and spans four rows:

```css
.foo-text {
  grid-row-start: 2;
  grid-row-end: 6;
}
```
