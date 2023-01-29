# Find a Phone Number With Regex

As a developer it is a necessity to know how to find and authenticate a phone number. How can one do this? Well he could write a complex script that had to take the entered string of numbers and figure out if it was a phone number, but is there a better way? Yes using regex one could complete this task in one simple if statement. In this tutorial the regex statement that can express whether or not something is a phone number will be explained.

## Summary

To find a phone number the regex statement
`/^[(]?\d{3}[)]?[-\s.]?\d{3}[-\s.]?\d{4,6}$/gm`
can be used. It looks for three digits inside optional parentheses followed by a dash, dot, or space then three digits a dash, dot, or space followed by four to six digests

## Table of Contents

-   [Anchors](#anchors)
-   [Quantifiers](#quantifiers)
-   [Grouping Constructs](#grouping-constructs)
-   [Bracket Expressions](#bracket-expressions)
-   [Character Classes](#character-classes)
-   [The OR Operator](#the-or-operator)
-   [Flags](#flags)
-   [Character Escapes](#character-escapes)

## Regex Components

### Anchors

The statement begins with `^` which means the beginning of the of a string or line

The statement ends with `$` which means the end of a string or line

### Quantifiers

The `?` matches between 0 or 1 of the preceding elements.

### Character Classes

The `[]` looks for anything inside in any order, however only one of the elements in the brackets needs to be true.

### Flags

The `/gm` are the flags the `g` is the global tag it causes the search to span across the entre document

The `m` is the multi line tag it causes the search to span the search through multiple lines

## Author

My name is Jett Crowther and I am an aspiring web developer enrolled in a coding bootcamp. I am hoping to achieve my dream of being a remote full stack developer.

[A link to my Github](https://github.com/Jett65)
