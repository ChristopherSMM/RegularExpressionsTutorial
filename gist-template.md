# Title (Regex Tutorial - HTML String)

This is my regex tutorial on how to use the HTML sting and their individual functions when used in coding, i will try my best to explain it as clearly and understandable as possible.

## Summary

The regex is used to identify a pattern in a string search algorithm through a function kown as (find) or (find and replace).

An example of the code is /^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/

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
The components for the Regex are /^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/
### Anchors (^abc123$)

We use anchors to define the search were the parameters begin and end.

Anything after ^ and before $ (symbols caret and dollar) are part of the search definition and the characters the follow after the caret(^) is identified by the position in the search.

The caret shows the beginning of the string where we have the algorithm to match the character and the dollar identifies the end of the string in the algorithm, this helps the system running the search parameter identify < and > charecters and anything between

(abc123 in the middle is just an example)

### Quantifiers

Quantifiers are used in the regex to find where our token string is matched to a pre-set mumber.

. +
This quantifier is used to match one or more charecters in the algorithm and placed to the left of the (+) and need to match at least once with any charecter.

. *
This quantifier lets the search know that it has to match 0 times or more.

. ?
This quantifier does the same as (*) and is optional but when impemented it makes the quantifier lazy making it match as few times as possible unlike the default which does the opposite making it considered greedy (matching as much as possible).

. {7,9}
This algorithm is set to have the charecters seven to nine charecters long.

. abc/cba
This is a match between abc and cba only.

### OR Operator

.|
This operator acts to be a boolean OR and makes a match of expressions before or after the | and is utilized in a group or a whole expression, this causes the search string to look for a match for what follows and precedes the |.

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
