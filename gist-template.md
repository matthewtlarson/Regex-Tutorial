# Regex Tutorial: Matching a Hex Value

Regex, or regular expressions, are sequences of characters that specify a search pattern in text. Regular expressions are strings of text that allow you to create patterns that can assist in matching, locating, and managing text. 

## Summary

I will be discussing the specific regex for mataching a hex value. Regexes can be used to validate a hexidecimal color code, which are values that tell the display how much of a color to show. In the description below, I will cover the many aspects of regexes and specifically the expression for matching a hex value. 

Matching a Hex Value – /^#?([a-f0-9]{6}|[a-f0-9]{3})$/

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

Anchors are used to declare an aspect of the string, but when they stand alone they are not considered regular expressions. For example, in the snippet of code above, the character ^ is an anchor and it is used to state the beginning of the following expression. On the other end of the expression, $ is also considered an anchor but its purpose is quite the opposite; in this case $ refers to the end of the regex. 

### Quantifiers

Quanitifiers are used to represent how often a specific character must be found in order to classify as a match. The ? in the regex above implies a value of 0 or 1; the $ is followed by the character # meaning it is optional in that instance. For example, the regex above contains {6} which implies that this quantifier will expect 6 characters in the string containing characters between a-f or integers between 0-9. 

### Grouping Constructs



### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

My name is Matthew Larson. My purpose in creating this document was to explore some computer science priciples and provide a thorough description of regexes. My goal as a developer is to broaden my skillset and continue implementing web technologies to build functional web applications in which I am passionate about. Linked below is my GitHub where you can locate some of my most recent work, or personal projects. I will continue to grow as a developer and plan on adding to this list throuhgout my journey.

<link href="https://github.com/matthewtlarson" />
