# Palindrome Checker


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Return true if the given string is a palindrome. Otherwise, return false.

Note: You'll need to remove all non-alphanumeric characters (punctuation, spaces and symbols) and turn everything into the same case (lower or upper case) in order to check for palindromes.


### Links

- Repo URL: [https://github.com/sadiejay/fcc-js-palindrome](https://github.com/sadiejay/fcc-js-palindrome)

## My process
- write pseudocode
- figure out palindrome function
- create regex to clean up input
- call function inside other function
### Built with
- JS


### What I learned


-  `reverse()` came in super handy.
    - If I hadn't come across that I probably would have created an array and created a loop to split the str, unshift each letter into new string, and then join.

  #### code snippets
```javascript 
let regexFunction = (str) => {
    let textLowerCase = str.toLowerCase();
    let cleanStr = textLowerCase.replace(/[^a-z0-9]/gi, '');
    return cleanStr;
} 
```
- I remembered to use the `.toLowerCase()` from my email generator 

### Continued development

- I want to create a UI to display:
    - client side input
    - revesed input
    - is palindrome? true / false
- Create my own tests from expected results given
### Useful resources

- [Three Ways to Reverse a String in JavaScript](https://www.freecodecamp.org/news/how-to-reverse-a-string-in-javascript-in-3-different-ways-75e4763c68cb/) - I felt like this basically told me the answer lol but then realized that I still needed to match the original input to the the reversed input.
- [Conditional (ternary) operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator) - I iwanted to use the ternary notation because someone that paired with me did in a previous project.
- [How to use a return value in another function in Javascript?](https://stackoverflow.com/questions/19674992/how-to-use-a-return-value-in-another-function-in-javascript) - This was pretty basic but I had all of my pieces figured out and couldn't understand how to piece the functions together.

## Author

- Github - [@sadiejay](https://github.com/sadiejay)

## Acknowledgments

- Class Cohorts fCC bootcamp cohort got me my start and now I'm finishing up!
