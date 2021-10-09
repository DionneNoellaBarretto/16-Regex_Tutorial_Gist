# Registry Expressions (RegEx) 101 Tutorial

**RegEx** OR Regular Expressions define a search pattern that can be used to search specific characters/formats in an input string. This tutorial explains how a specific regular expression, or regex, functions by breaking down each part (component i.e. [#regex-components]())of the expression and describing what it does.

## Summary

The following regular expression can be used to verify that user input is a valid email address:

👉 Matching an Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

**Note:** Each component of this regex has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the `@` symbol, followed by a domain.

But ***this is not all***, let's proceed with reviewing the following expressions as well in the text to follow 

👉 Matching a Hex Value: `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`


👉 Matching a URL: `/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`

👉 Matching an HTML Tag: `/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/`


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors


### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

<a href="https://github.com/DionneNoellaBarretto">Dionne Noella Barretto</a>
<a target="_blank" rel="noopener noreferrer" href="https://dionnenoellabarretto.github.io/DionneNoellaBarretto_Portfolio/"><img src="https://avatars.githubusercontent.com/dionnenoellabarretto?s=150&amp;v=1" alt="@dionnenoellabarretto" style="max-width:100%;"></a>
