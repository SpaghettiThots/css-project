## String.prototype.toUpperCase()
##### What is it?
This refers to a method of the `String` object in JavaScript.

##### What does it do?
It converts a string to uppercase.

##### Syntax
`string.toUpperCase()`, where `string` is the sequence of characters to be turned to uppercase.

##### What does it return?
A copy of the string, with each lowercase letter converted to its uppercase equivalent [if it exists].

**Note that it returns a copy of the string and not the string itself turned to uppercase. This is due to the intrinsic *immutability* property of strings.**

##### An Example
```js
//Define a string
var test-string = "Eat tHat frog.";

//Declare another variable to hold the output of string operation
var test-result = test-string.toUpperCase();

//Log test-result to console
console.log(test-result);  //"EAT THAT FROG."
```

##### Browser Support
`String.prototype.toUpperCase()` is well-supported across all major browsers (desktop and mobile) with no reported quirks.

