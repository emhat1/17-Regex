# Regex (Regular Expression) Tutorial

Regular expressions (Regex) in coding refer to a short series of characters that can define a search pattern.  It includes accepted characters (and by default, excludes non-accepted characters)


## Summary

The regex to recognise a valid URL looks for both accepted characters and correct formatting.  Ultimately, it identifies whether the provided string is a valid URL.

An example of such a regex is:
````
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/
```` 


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
An example of a regex to identify a URL is:
````
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/
```` 
This can be broken down into its various segments


### Anchors
The two primary anchors in this example are ^ (at the beginning) and $ (at the end).

When the ^ anchor appears at the start of the regex, the search will match with any string that begins with the characters immediately following ^.

When the $ anchor appears at the end of the regex, the search will match with any string that ends with the characters immediately preceding $.

By including both of these anchors, the search will match exactly what is included between ^ and $.


### Quantifiers



### Grouping Constructs



### Bracket Expressions



### Character Classes



### The OR Operator



### Flags

Although flags are not applicable to the example given above, they can alter how a regex identifies a string.  Following the final / a flag can be added to further tailor the search. Flags include:

 - g (global flag) will recognise all instances of the string in a given input
 - m (multiline flag) will recognise the start and end of a line where the pattern occurs, as opposed to just the string itself
 - i (insensitive flag) will identify the string irrespective of case


### Character Escapes



## Author

Erin Hatherell is an aspiring full stack web developer based in Melbourne, Australia - [mambru82 on GitHub](https://github.com/emhat1)