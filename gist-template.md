# Regex-Tutorial

 A regular expression, or regex for short, is a sequence of characters that defines a specific search pattern. When incorporated into code or search algorithms, regular expressions enable the identification of particular patterns of characters within a string. Additionally, they can be utilized to locate and substitute a character or sequence of characters within a string. Furthermore, regular expressions are commonly employed for input validation purposes.

## Summary

I have selected a regular expression for an email address and this is what the regular expression is:
Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
This regular expression has two anchors. The caret ^ and the dollar $ sign. The caret matches at the start of the string the regex pattern is applied to. As for the dollar sign, it matches at the end of the string the regex pattern is applied to.
### Quantifiers
My regular expression has a greedy quantifier which is the plus symbol. It repeats the previous item once or more. Their is no limit to the length of the string to the left of the @ sign. 

### OR Operator
The OR Operator is the vertical line which represents OR and is not present in the regular expression.

### Character Classes
My regular expressions has several char classes determined by hyphens. For example the first char class allows any letters between a-z. As for the second, it allows any numbers between 0-9. 


### Flags
The / is used to delimit the expression. And would come before the caret and after the dollar sign. After the closing / g = global search, i = case sensitive search, m = multi-line search, are some flags that may be used. The flags in my regular expression represent the beginning and the end of the expression.



### Grouping and Capturing

### Bracket Expressions
Using brackets allows a regex to match specific characters in a range. So, [a-z] is not looking for a or - or z, but actually looking for any letters a through z. And in the brackets the "-" is not taken literally in the cases of a-z or 0-9. But after the \ to escape the period it is recognized as a literal "-".

### Greedy and Lazy Match
A greedy match will match as much as possible while the lazy match will try to match as little as possible. In matches in the email regex are greedy and will match as much as possible.

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author
John Elmore

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
