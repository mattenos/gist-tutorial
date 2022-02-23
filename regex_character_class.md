# Regex - Character Classes

Character classes allow programmers to distinguish between character types.

## Summary

Character classes are data that appears within square brackets. They act as an or-like expression. I'll be explaining how you can match a series of numbers using a character class.

```javascript
var newData= "753 167 65655 6851 54545 88555 25";
var regexpFourDigits = /\b\d{5}\b/g;
// \b indicates the boundaries of the class,
// \d{4} indicates a digit. the 4 represents the number of digits to match.

console.table(newData.match(regexpFourDigits));
// ['65655', '54545', '88555']
```

## Author

Matt Enos is currently enrolled in GT Coding Bootcamp. Here is a link to their GitHub (https://github.com/mattenos).