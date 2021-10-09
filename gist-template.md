# Registry Expressions (RegEx) 101 Tutorial

**RegEx** OR Regular Expressions define a search pattern that can be used to search specific characters/formats in an input string. This tutorial explains how a specific regular expression, or regex, functions by breaking down each part (component i.e. [#regex-components](https://github.com/DionneNoellaBarretto/16-Regex_Tutorial_Gist/blob/main/gist-template.md#regex-components))of the expression and describing what it does.

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


<table width="100">
<tr>
<td align='center'> <strong>Matching a Hex Value </strong></td>
<td align='center'> <strong>Matching a URL</strong> </td>
<td align='center'> <strong>Matching an HTML Tag</strong></td>
</tr>
<tr>

<td align='center' > 👉`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/` </td>
<td align='center'> 👉`/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`</td>
<td align='center'> 👉 `/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/`</td>
</tr>
<tr>
<td align='center'> The string must be 6 characters long and start with a '#' followed by lower case letters and/or characters OR could be 3 characters long and the '#' is followed by only by lower case letters and/or characters</td>
<td align='center'> The string must with an 'https://' characters followed by lower case letters any length long, followed by a dot and again followed by lower case letters and/or characters OR could be 3 characters long and the '#' is followed by only by lower case letters and/or characters</td>
<td align='center'>c</td>
</tr>
</table>



### Anchors
An *Anchor* symbolized as ^ (beginning anchor) or $ (closing anchor) signifies a string that starts with characters following it

### Quantifiers
? (use for optional characters) and  * symbols are common *Quantifiers* seen in a regex
### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author
This RegEx Tutorial was created by <a href="https://github.com/DionneNoellaBarretto">Dionne Noella Barretto</a>
