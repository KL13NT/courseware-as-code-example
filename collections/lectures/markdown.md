---
title: Using Markdown
description: A sample file to show how to use markdown in CaC.
---

# Markdown

Markdown is a lightweight markup language that you can use to add formatting
elements to plaintext text documents. This article lays out some examples of how it works
and how is can be used in CaC, you can also read more about it in [Markdown
Cheatsheet].

You can use the [Markdown All in One] and [Markdown Shortcuts] VSCode extensions
to easily format markdown files, add and automatically update table of contents
and tables, etc. This combination makes markdown editing really fun!

This document requires you view the source to understand how it works.

## Headers

```markdown
# This is an h1 tag (biggest)

## This is an h2 tag

### This is an h3 tag

#### This is an h4 tag

##### This is an h5 tag

###### This is an h6 tag (smallest)

For underline style:

# Alt-H1

## Alt-H2
```

Don't skip header levels, for example, don't go from an h1 to an h3. Skipping
ruins the accessibility and SEO of the output pages.

## Paragraphs

```markdown
Paragraphs shouldn't have tabs or spaces in the beginning. By default new lines
in the output are created by leaving an empty line between two paragraphs or
elements in general.

This is another paragraph after the first. You can have it in any formatting you like! Markdown is really fun!
```

Paragraphs shouldn't have tabs or spaces in the beginning. By default new lines
in the output are created by leaving an empty line between two paragraphs or
elements in general.

This is another paragraph after the first. You can have it in any formatting you like! Markdown is really fun!

## Emphasis

```markdown
_This text will be italic (This is the best practice)_
**This text will be bold (This is the best practice)**
_You **can** combine them_
```

_This text will be italic (This is the best practice)_

**This text will be bold (This is the best practice)**

_You **can** combine them_

## Lists

### Unordered

```markdown
- Item 1
- Item 2
  - Item 2a
  - Item 2b
```

- Item 1
- Item 2
  - Item 2a
  - Item 2b

### Ordered

```markdown
1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b
```

1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b

## Blockquotes

As Abraham Lincoln once said:

```markdown
> The problem with quotes found on the internet is they often are not true.
```

> The problem with quotes found on the internet is they often are not true.

## Code

### Inline

```markdown
`f(x) = x^2` and `f(x) = x^2` are valid inline code.
```

`f(x) = x^2` and `f(x) = x^2` are valid inline code.

### Block

I recommend keeping in code in fences ` ``` ` (called Blocks). This gives you syntax
highlighting and are easier to type.

````markdown
```java
public static void main(String[] args) {
    System.out.println("Never gonna give you up");
}
```
````

```java
public static void main(String[] args) {
    System.out.println("Never gonna give you up");
}
```

## Links

### Inline

You can create links to anything you want by using the following syntax: `[link text](url)`.

```markdown
This is how to create links with the href embedded in the link itself: [Google](https://www.google.com).
```

This is how to create links with the href embedded in the link itself: [Google](https://www.google.com).

### Reference

You can create reference links which are useful when you use the same link
multiple times on the same page. They're also recommended because they make the
Markdown source easier to read. References are case-insensitive.

```markdown
This is a paragraph with reference-style links! Visit [Google] and [Facebook]! You can also have numbered references and they'd still work. [YouTube][1] is an example. References to files also work! [file].

[google]: https://www.google.com
[facebook]: https://www.facebook.com
[1]: https://www.youtube.com
[file]: ./latex.md
```

This is a paragraph with reference-style links! Visit [Google] and [Facebook]! You can also have numbered references and they'd still work. [YouTube][1] is an example. References to files also work! [file].

[google]: https://www.google.com
[facebook]: https://www.facebook.com
[1]: https://www.youtube.com
[file]: ./latex.md

### Angle Brackets

```markdown
URLs in angle brackets will automatically get turned into links. <http://www.example.com>.
```

URLs in angle brackets will automatically get turned into links. <http://www.example.com>.

## Tables

You can add tables in markdown to be rendered as accessible HTML tables. The
following code produces the output below:

```markdown
| Column A | Column B | Column C |
| -------- | -------- | -------- |
| A1       | B1       | C1       |
| A2       | B2       | C2       |
| A3       | B3       | C3       |
```

| Column A | Column B | Column C |
| -------- | -------- | -------- |
| A1       | B1       | C1       |
| A2       | B2       | C2       |
| A3       | B3       | C3       |

[markdown cheatsheet]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
