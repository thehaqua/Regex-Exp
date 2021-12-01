# Title (replace with your title)

Regex, short for Regular Expression, detects paterns within a string. I am going to use Email Validationn as an example. Email validation prevents issues with creating emails that are unregistered as well as cleans up the back end of your program.

## Summary

 I am using Email Validation (Expression: ^([a-zA-Z0-9_-.]+)@([a-zA-Z0-9_-.]+).([a-zA-Z]{2, })$). I touched on it a bit, but Email validation is self explanitory, as it varifies emails. 

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

Anchors begin and end a regex expression- the expression begins with ^ and always ends with $. 

### Quantifiers

Quantifiers gaige the amount of instances needed to find a match. It is divided into different parts, being name, domain and TLD. 

### Grouping Constructs

Found by looking into parentheses, the groups are separated into groups this way. The Name, Domain, and TLD being separated as such:  /^([a-z0-9_.-]+), @([\da-z.-]+)\ 3, and .([a-z.]{2,6})$/.

### Bracket Expressions

Anything surrounded by brackets is a bracket Expression. [a-z0-9_.-] locates any letter that is lowercase, and any number. [\da-z.-] locates any letter that is lowercase and assigns each one it finds a number. [a-z.] locates any lowercase letter as well as a period.

### Character Classes

Character class splits different special characters up, an email needs an @ symbol and a period to be valid, so this expression explicity finds them.

### The OR Operator

The OR Operator lets the Regex choose to find two different character types. In this expression, it is used to let the validator find letters OR numbers.

### Flags

This expression does not use flags.

### Character Escapes

The character escape, usually a \ placed before the curly brace lets the Regex know to search for the information within the brackets and not at the beginning of the quantifier. 

## Author

https://github.com/thehaqua
