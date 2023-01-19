---
title: Using Markdown
description: A sample file to show how to use markdown in CaC.
---

# Markdown

Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents, and here is some examples of how it works and how is can be used in CaC, you can also read more about it in [Markdown Cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## Headers

# This is an h1 tag
## This is an h2 tag
### This is an h3 tag
#### This is an h4 tag
##### This is an h5 tag
###### This is an h6 tag

Don't skip header levels, for example, don't go from an h1 to an h3.  
This improves the accessability of the output pages.
## Paragraphs

paragraphs shouldn't have tabs or spaces in the beginning.

you can also write line  
with double spaces to have multi line paragraphs.

## Emphasis

*This text will be italic (This is the best practice)*  
_This will also be italic_

**This text will be bold (This is the best practice)**  
__This will also be bold__

*You **can** combine them*

## Lists

### Unordered

* Item 1
* Item 2
  * Item 2a
  * Item 2b

### Ordered

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

## Blockquotes

As Abrahim Lincoln said:

> The problem with quotes found on the internet is they often are not
> true.

## Code

### Inline

`f(x) = x^2` and `f(x) = x^2` is a function.

### Block

```java
public static void main(String[] args) {
    System.out.println("Never gonna give you up");
}
```

## Links

### Inline

You can create links to anything you want by using the following syntax: `[link text](url)`.

For example, to create a link to [Google](https://www.google.com), you'd write this in Markdown: `[Google](https://www.google.com)`.

### Reference

You can create reference like for example [Google][google] or [Facebook][facebook], this is useful when you have multiple links to the same place like in mentioning appendices.

[google]: https://www.google.com
[facebook]: https://www.facebook.com


