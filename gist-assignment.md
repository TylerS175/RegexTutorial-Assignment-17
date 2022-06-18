# Regex Tutorial - Understanding the Concept - 
- Hex Value /^#?([a-f0-9]{6}|[a-f0-9]{3})$/

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
The "or" operator within a regular expression is defined using the | element. It indicates it could either of the components that we are seperating with the |. ([a-f0-9]{6} |  [a-f0-9]. See how the | is seperating these 2 components. The hex value could be 6 characters is ([a-f0-9]{6} or 3 character [a-f0-9]{3}

### Character Classes
Character classes are components within our regular expression that tells us what type of characters to expect. For instance you identified the classes with brackets []. Look at these 2 character classes that share the same value. If you breakdown the class a-f it will be known to search for letters a-f and the 0-9 class will search for the numbers 0-9 based on what it is being told. 

### Flags
Flags affects the search in regular expressions. It is an optional parameter to a regex that modifies its behavior of searching. In javascript regex, there is a total of 6 flags, each serving a different purpose. In this case, we have a multline flag cause of the ^ & $ seen in /^#?([a-f0-9]{6}|[a-f0-9]{3})$/ 

i - Ignore Casting (Makes the expression search case-insensitively)
g - Global (Makes the expression search for all occurences)
s - Dot All (Makes the wild character . match newlines as well)
m - Multiline (Makes the boundary characters ^ and $ match the beginning and ending of every single line instead of the beginning and ending of the whole string. 


### Grouping and Capturing
Grouping and capturing is a way to treat multiple characters as a single unit it can be found in group set of parentheses. For example regular expression (dog) creates a single group containing the letters "d", "o", and "g". 

### Bracket Expressions
This matches any character in the square brackets. Take for example [nN] or [oO] that can match for words such as no, No, nO, and NO. Another example is gr[ae]y that matches both spellings of the word 'grey' that is either go two different directions gray or grey

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Greetings, my name is Tyler Shifflett. I am currently enrolled with coding/web development at University of Richmond to become a successful website creator and start career as Front End Develop and freelancer. 
GitHub Link: https://github.com/TylerS175 