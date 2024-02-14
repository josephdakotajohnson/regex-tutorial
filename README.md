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

- The `^` anchor at the beginning is a way to determine where the matches can begin.

- The `$` anchor at the ending is a way to determine where the matches can end.

### Quantifiers

- The `+` quantifier stands for one or more times that the character class or group must be applied.

- The `{2,5}` quantifier specifies a that there must be between 2 and 5 of the acceptable characters preceding it.

### Grouping Constructs

- `([a-zA-Z0-9_\-\.]+)`: matches one or more occurrences of the characters within the brackets.  This is used to match the username part of th email address.

- `([a-zA-Z0-9_\-\.]+)`: matches one or more occurrences of the characters within the brackets.  This is used to match the domain name part of the email address.

- `([a-zA-Z]{2,5})`: matches between 2 and 5 occurrences of the characters within the brackets.  This is used to match the top-level domain (TLD) part of the email address.

### Bracket Expressions

- `[a-zA-Z0-9_\-\.]`: means that only uppercase or lowercase alphabetical characters, numbers, and `-` and `.` are allowed in this section.  This is used to match the username part of the email address.

- `[a-zA-Z0-9_\-\.]`: means that only uppercase or lowercase alphabetical characters, numbers, and `-` and `.` are allowed in this section.  This is used to match the domain name part of the email address.

- `[a-zA-Z]`: means that only uppercase or lowercase alphabetical characters are allowed in this section.  This is used to match the top-level domain (TLD) part of the email address.

- It the first character in the list is a caret `^`, it matches any character not in the list and it isn't specified whether it matches with an encoding error.

### Character Classes

- `a-zA-Z0-9_\-\.`: means that only uppercase or lowercase alphabetical characters and numbers are allowed in this section.  This is used to match the username part of the email address.

- `a-zA-Z0-9_\-\.`: means that only uppercase or lowercase alphabetical characters and numbers are allowed in this section.  This is used to match the domain name part of the email address.

- `a-zA-Z`: means that only uppercase or lowercase alphabetical characters are allowed in this section.  This is used to match the top-level domain (TLD) part of the email address.

### The OR Operator

- This is no OR(`|`) in this regex expression.

### Flags

- Flags are optional parameters to regex expressions that modify its behavior of searching.  These are the flags, `i`, `g`, `s`, `m`, `y`, and `u`.  There are no flags in this regular expression.

### Character Escapes

- A `\` is an escape code that restores the literal original meaning of the preceding character.  This means that `-` and `.` are allowed in the first two sets of Character Classes.

## Author

- Joseph Dakota Johnson

---