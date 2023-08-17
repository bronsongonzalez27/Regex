# Regular expressions and their functional purposes

Hello, my name is Bronson Gonzalez, I am going to teach you about regex's (regular expressions).

## Summary

RegEx, is a short term for the word regular expressions.  Regex are a set of characters that creates patterns. RegEx can be used to find information in a database.
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
Anchors determine and specify positions within the text where matches occur, the most commonly used anchors are "^", matching at the start of a line, and "$" matching at the end of a line.
### Quantifiers
Quantifiers are used to specify hows many times a particular element or group occurs, common examples for quantifiers include :

* "*": Matches zero or more occurrences.
* +: Matches one or more occurrences.
* ?: Matches zero or one occurrence.
* {n}: Matches exactly n occurrences.
* {n,}: Matches n or more occurrences.
* {n,m}: Matches between n and m occurrences.
### OR Operator
OR operators are used in regular expressions to match patterns. It's represented by a vertical bar "|" character. When used in a regex pattern, it will match the left or right side, an example of this would be rainy|sunny.
### Character Classes
Character classes are used to define a set of characters that will match at a specified position. 
Some examples of this would include:
* [a-z]: Matches any lowercase letter.
* [0-9]: Matches any digit.
* [A-Za-z]: Matches any letter (case-insensitive).
### Flags
Flags, or modifiers, modify the behavior of a regex matching, some examples of flags are:
* i: Case-insensitive matching.
* g: Global matching (find all occurrences).
* m: Treat the input as multiple lines.
### Grouping and Capturing
Grouping and matching parentheses "()" are used to group eleements together. This is useful to apply quantifiers to a group of characters. Groups also capture the matched string for later purposes.
### Bracket Expressions
Bracket expressions "[]" define a character class. Their purpose allows you to match a single character from a selected set of characters, for example '[aeiou]'
### Greedy and Lazy Match
Greedy and Lazy match 
### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Thank you for listening and reading my tutorial explaining Regex terms. For further information or any questions you will have please contact me here : https://github.com/bronsongonzalez27


