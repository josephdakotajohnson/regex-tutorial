# regex-tutorial
I want to write a tutorial on a custom-made regular expression (regex).

[![Regex](https://img.shields.io/badge/Regex-Reference-blue)](https://en.wikipedia.org/wiki/Regular_expression)

- 

## Summary

- I want to write a tutorial on a custom-made regular expression (regex).

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)
- [Author](#author)

## Regex Components

- This regex features an email address:  `^([a-zA-Z0-9_\-\.]+)@([a-zA-Z0-9_\-\.]+)\.([a-zA-Z]{2,5})$`

### Anchors

- The '^' anchor at the beginning is a way to limit how it matches the string be stating where the matches can begin and end.

### Quantifiers

- The '

### Grouping Constructs

- `([a-zA-Z0-9_\-\.]+)`: matches one or more occurrences of the characters within the brackets.  This is used to match the username part of th email address.

- `([a-zA-Z0-9_\-\.]+)`: matches one or more occurrences of the characters within the brackets.  This is used to match the domain name part of the email address.

- `([a-zA-Z]{2,5})`: matches between 2 and 5 occurrences of the characters within the brackets.  This is used to match the top-level domain (TLD) part of the email address.

### Bracket Expressions

- 

### Character Classes

- 

### The OR Operator

- 

### Flags

- 

### Character Escapes

- 

## Author

- 

---