---
Title: ".contentEquals()"
Subjects:
  - "Computer Science"
Tags:
  - "Strings"
  - "Methods"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-java"
  - "https://www.codecademy.com/learn/paths/computer-science"
---

## Definition

Returns `true` if the sequence of characters in the string is equal to the content of the specified string. If not, returns `false`.

## Syntax

```java
string.contentEquals(CharSequence characters)
```

- `characters` (required): A character value specifies the sequence of characters to be searched for.

## Example 1

Call the `.contentEquals()` method on the `word` string with the arguments `"water"` and `"watermelon"`:

```java
class isContentEqual {
  public static void main(String[] args) {
    String word = "watermelon";

    System.out.println(word.contentEquals("water"));
    System.out.println(word.contentEquals("watermelon"));
    // Output: false
    // Output: true
  }
}
```
