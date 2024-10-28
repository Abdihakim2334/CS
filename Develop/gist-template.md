# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary
This regex pattern that I will be showing is made for matching basic URLs, allowing for optional protocols and paths. The regex pattern that will be showing is dispayed below.

`/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`

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

Anchors are used to declare the positions in the string. In the regex, ^ asserts the start of the string, and $ asserts the end. This makes sure that the whole string must comply to the regex pattern.

### Quantifiers
Quantifiers state the frequency of occurrence for the preceding element in a regex. In this particular regex, the ? indicates that the preceding component (the protocol) is optional, so it allows it to appear either once or not even at all. Meanwhile, the * quantifier permits the path to occur multiple times, including the possibility of it being absent entirely.


### Grouping Constructs

Grouping constructs, represented by parentheses (), are used to serve to combine the sections of the regex for the application of quantifiers or to also capture matched segments. For instance, the expression (https?:\/\/)? encloses the protocol portion, while ([\da-z\.-]+) encompasses the domain.



### Bracket Expressions

Bracket expressions [] are used to define a set of characters that can match at that specific position. For example, [\da-z\.-] matches any digit, lowercase letter, hyphen, or dot.

### Character Classes

Character classes are pretty much very similar to bracket expressions but can also be more specific. In the regex, \w (within [\/\w \.-]*) matches any word character , while \d matches any digit.


### The OR Operator
There is actually no OR Operator in this regex.


### Flags

This regex does not use flags. Flags are used to change the conduct of the regex.

### Character Escapes

Character escapes, shown with a backslash \, actually let you treat special characters as normal characters. For example, \/ is used to match a forward slash, so it will not  get confused with a regex delimiter.


## Author

This assignment was done by Abdihakim Abdirahman. 

Github- https://github.com/Abdihakim2334
