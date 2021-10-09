# Registry Expressions (RegEx) 101 Tutorial

**RegEx** OR Regular Expressions define a search pattern that can be used to search specific characters/formats in an input string. This tutorial explains how a specific regular expression, or regex, functions by breaking down each part (component i.e. [#regex-components](https://github.com/DionneNoellaBarretto/16-Regex_Tutorial_Gist/blob/main/gist-template.md#regex-components))of the expression and describing what it does.

## Summary

The following regular expression can be used to verify that user input is a valid email address:

👉 Matching an Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

**Note:** Each component of this regex has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the `@` symbol, followed by a domain.

But ***this is not all***, let's proceed with reviewing the following expressions as well in the text to follow 


<table width="100">
<tr>
<td align='center'> <strong>Matching a Hex Value </strong></td>
<td align='center'> <strong>Matching a URL</strong> </td>
<td align='center'> <strong>Matching an HTML Tag</strong></td>
</tr>
<tr>
<td align='center' > 👉^#?([a-f0-9]{6}|[a-f0-9]{3})$ </td>
<td align='center'> 👉^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$</td>
<td align='center'> 👉 ^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$</td>
</tr>
<tr>
<td align='center'> The string must be 6 characters long and start with a '#' followed by lower case letters and/or numbers OR could be 3 characters long and the '#' is followed by only by lower case letters and/or numbers </td>
<td align='center'> The string must start with an 'https://' characters followed by lower case letters any length long, followed by a dot and again followed by lower case letters of length 2 to 6 characters </td>
<td align='center'> The string must start with a "<"(without the quotes) followed by lower case letters of any length followed by a closure brace ">" (without the quotes) and then ultimately appended with a closing tag starting with "< /" (without the quotes and space) and ending with ">" (without the quotes) </td>
</tr>
<tr>
<td align='center'> <em>Example: #00ff00 or #0f0 or #000000 or #123 </em></td>
<td align='center'> <em>Example: https://github.com or https://example.in </em></td>
<td align='center'> <em>Example: <a href="https://www.w3schools.com/TAGS/default.ASP" target="_blank"> Html Tags</a> </em></td>
</tr>
</table>


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
An *Anchor* symbolized as ^ (beginning anchor) or $ (closing anchor) signifies a string that starts with characters following it.

### Quantifiers
? (use for optional characters) and  * symbols are common *Quantifiers* seen in a regex. 

### Grouping Constructs
As patterns within a string search begin to get more complicated, *Grouping Contstructs* becomes essential to partition regex using () in order to match only a portion of the string at a time.

***Note:*** In the HTML Example above - Multiple groups are bounded by parentheses like for example ?: is grouped to designate them as non-capturing - So long as ?: is not included regex will keep count of all capturing groups bounded by ().

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author
This RegEx Tutorial was created by <a href="https://github.com/DionneNoellaBarretto">Dionne Noella Barretto</a>
