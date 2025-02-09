---
Title: "overflow"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Positioning"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition

Defines how a block level element should handle content that goes beyond its boundaries.

## Syntax

```css
overflow: <value>
```

where `<value>` can be one of the following:

- `visible`: the default value. No content will be clipped and a scrollbar will not appear.
- `hidden`: content will be clipped and no scrollbar will appear.
- `scroll`: content will be clipped and a scrollbar will appear.
- `auto`: content will be clipped if it does not fit in the containing block, and a scrollbar will appear if it does.
- Keyword values: `initial`, `inherit`, `revert`, `unset`.


## Example 1

Clip any content that overflows without providing a scrollbar to view overflow content.

```css
.view-box {
  overflow: hidden;
}
```

## Example 2

Provide a scrollbar and clip any content that overflows.

```css
.view-box {
  overflow: scroll;
}
```

## Example 3

Provide a scrollbar only if overflow contents exists.

```css
.view-box {
  overflow: auto;
}
```