---
Title: ".extend()"
Subjects:
  - "Data Science"
  - "Computer Science"
Tags:
  - "Lists"
  - "Methods"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-python-3"
  - "https://www.codecademy.com/learn/paths/data-science"
  - "https://www.codecademy.com/learn/paths/computer-science"
---

## Definition 

Adds list elements to end of the list.

## Syntax

```py
list.append(iterable)
```

This will place passed in iterable (list, tuple, or string) as new elements at the very end of the list.

`.append()` does not return any value.

## Examples

To add `grocery_new` to the end of the `grocery` list:

```codebyte/python
grocery = ['blueberries', 'eggs', 'artichoke']
grocery_new = ['milk', 'cookies']

grocery.extend(grocery_new)

print(grocery)
# Output: ['blueberries', 'eggs', 'artichoke', 'milk', 'cookies']
```

It works for any other type of iterables:

```codebyte/python
to_do_list = ['respond to email', 'check github']
targets = (4, 1, 6, 20)

to_do_list.extend(targets)

print(to_do_list)
# Output: ['respond to email', 'check github', 4, 1, 6, 20]
```
