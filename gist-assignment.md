# Regex Tutorial - Understanding the Concept - Hex Value /^#?([a-f0-9]{6}|[a-f0-9]{3})$/

Regular expressions are patterns that are used to match character combinations in strings. Regular expression is a composed of simple characters for an example /abc/ or a combination of simple and special characters such as /ab*c/ or /Chapter /d/d/d. Another way of using Regex In a regular expression the metacharacter ^ means "not". So, while "a" means "match lowercase a", "^a" means "do not match lowercase a".

## Summary

In this summary, we are going to be reviewing the components of regular expression that are used to match Hex Values.  Hexadecimal code is a system by which any specific color can be described accurately to a computer, ensuring consistency and accuracy in an electronic display. A hexadecimal color value is a six-digit code preceded by a # sign; it defines a color that is used in a website or a computer program. /^#?([a-f0-9]{6}|[a-f0-9]{3})$/

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
Anchors - ^ & $
- Regular Expression anhcors that allow you to match a position before and after characters. Example ^ is a caret anchor matches the beginning of the text while the $ is the dollar anchor that matches the end of the text. If you were applied ^A to ABC matches A. Now using ^B does not match at all because it cannot be match right after the start of the string. Now using $ matches right after the last character in the string. Example C$ would match C in ABC scenario, while if you were use A$ or B$ it does not match at all. 

### Quantifiers
Quantifiers indicate numbers of character or expressions to match. They specify how many instances of a character, group, or character class must be present in the input of a match to be found. If the ",+,?, {}" characters are found within regular expressions, they are considered quantifiers. The quantifer ? means zero or one {0,1}. A number in curly braces {n} is the simplest quantifier. As you can see we have {6} is a triplet format and {3} is shorthand format. There is two types of formats a hex triple is six digit, three-byte hexadecimal number used in HTML, CSS, and other computer application to represent colors. The shorthand hex abberivates RRGGBB CSS colors into 3-character RGB shorthand. 

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Greetings, my name is Tyler Shifflett. I am currently enrolled with coding/web development at University of Richmond to become a successful website creator and start career as Front End Develop and freelancer. 
GitHub Link: https://github.com/TylerS175 