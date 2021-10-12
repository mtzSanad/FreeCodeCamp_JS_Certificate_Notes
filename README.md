# FreeCodeCamp_JS_Certificate_Notes

* JavaScript provides eight different data types which are undefined, null, boolean, string, symbol, bigint, number, and object.
* When JavaScript variables are declared, they have an initial value of undefined. If you do a mathematical operation on an undefined variable your result will be NaN which means "Not a Number".If you concatenate a string with an undefined variable, you will get a literal string of undefined.
* Strings are immutable b='asdfasdf' b[0]='S' is error.
* In arrays push add element to end, pop remove element from end, shift remove element from first unshift add element to first of array.
* Variables which are defined outside of a function block have Global scope. This means, they can be seen everywhere in your JavaScript code.
* Variables which are declared without the var keyword are automatically created in the global scope. This can create unintended consequences elsewhere in your code or when running a function again. You should always declare your variables with var.
* Variables which are declared within a function, as well as the function parameters, have local scope. That means they are only visible within that function.
* It is possible to have both local and global variables with the same name. When you do this, the local variable takes precedence over the global variable.
* A function can include the return statement but it does not have to. In the case that the function doesn't have a return statement, when you call it, the function processes the inner code but the returned value is undefined.
* everything to the right of the equal sign is resolved before the value is assigned. This means we can take the return value of a function and assign it to a variable.
* Strict equality (===) is the counterpart to the equality operator (==). However, unlike the equality operator, which attempts to convert both values being compared to a common type, the strict equality operator does not perform a type conversion.
* typeof
* Like the equality operator, the greater than operator will convert data types of values while comparing.
* switch case values are tested with strict equality (===). The break tells JavaScript to stop executing statements. If the break is omitted, the next statement will be executed.
* Objects are similar to arrays, except that instead of using indexes to access and modify their data, you access the data in objects through what are called properties.
* There are two ways to access the properties of an object: dot notation (.) and bracket notation ([]), similar to an array.
* You can add new properties to existing JavaScript objects the same way you would modify them.
* delete ourDog.bark; to delete property.
* Sometimes it is useful to check if the property of a given object exists or not. We can use the .hasOwnProperty(propname) method of objects to determine if that object has the given property name. .hasOwnProperty() returns true or false if the property is found or not.
* Recursive functions must have a base case when they return without calling the function again (in this example, when n <= 0), otherwise they can never finish executing.
* JavaScript has a Math.random() function that generates a random decimal number between 0 (inclusive) and 1 (exclusive). Thus Math.random() can return a 0 but never return a 1.
* Use Math.random() to generate a random decimal.Multiply that random decimal by 20.Use another function, Math.floor() to round the number down to its nearest whole number.
* The parseInt() function parses a string and returns an integer, it returns NaN if not a number.
* The parseInt() function parses a string and returns an integer. It takes a second argument for the radix, which specifies the base of the number in the string. The radix can be an integer between 2 and 36.
* The conditional operator, also called the ternary operator, can be used as a one line if-else expression.
