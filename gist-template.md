# Regex-Tutorial Match Email

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
Parenthases are used to group parts of the expression together. In /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ the username is grouped, then the provider name is grouped, but between them is an @ symbol so nothing affecting those groups affects the @ symbol and the regex will just look for a single @ symbol between those two groups.


### Bracket Expressions
Using brackets allows a regex to match specific characters in a range. So, [a-z] is not looking for a or z, it's actually looking for any letters a through z. And in the brackets the "-" is not taken literally in the cases of a-z or 0-9. But after the \ to escape the period it is recognized as a literal "-".


### Greedy and Lazy Match
A greedy match will match as much as possible while the lazy match will try to match as little as possible. In matches in the email regex are greedy and will match as much as possible. My regex includes greedy matches. Since it includes the + Quantifier, it will match as many times as possible giving back as needed. Another greedy Quantifier used in my regex is the {} when matching `{2,6} for the last capture group.


### Boundaries
Boundaries \b is one side of the word and the other side is not a word character ( a string or a space).


### Back-references
- [Introduction to regular expressions video](https://www.youtube.com/watch?v=7DG3kCDx53c)
- [Regular-Expressions.info](https://www.regular-expressions.info/)
- [MDN Web Docs - Regular-Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)
- [3.ntu.edu - Regex](https://www3.ntu.edu.sg/home/ehchua/programming/howto/Regexe.html)
- [Regular-Expressions101](https://regex101.com/)
- [Regex Tutorial: Matching a Username](https://coding-boot-camp.github.io/full-stack/computer-science/regex-tutorial)
- [Regex cheatsheet](https://dev.to/catherinecodes/a-regex-cheatsheet-for-all-those-regex-haters-and-lovers--2cj1)
- [Regex101](https://regexone.com/)


### Look-ahead and Look-behind
Look-ahead and Look-behind regex components are also known as "lookarounds". They have no boundaries and will start looking whether there's a match or not. These are used to look for specific characters that are either followed by or before a specific character or sequence of characters to find a match. An example of this it to look for a $ followed by a number to find all the prices on a page. My code for email matching does not use a look-ahead or a look-behind component.



## Author
Hi my name is John Elmore and I enjoy coding. Please feel free to view my projects.

https://github.com/Letmego1st

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
