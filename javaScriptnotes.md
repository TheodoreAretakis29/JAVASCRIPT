# JAVASCRIPT
- The console.log() command is used to print, or log, text to the console. Consider the following example: console.log("Hello!");
- Strings: Any grouping of keyboard characters (letters, spaces, numbers, or symbols) surrounded by single quotes ('Hello') or double quotes ("World!"). In the example above, 'New York City' is a string.
- Numbers: Any number, including numbers with decimals: 4, 1516, .002, 23.42. In the example above, 40.7 is a number.
- Booleans: Either true or false, with no quotations. In the example above, true is a boolean.
- Null: Can only be null. It represents the absence of value.
- JavaScript supports the following math operators:
Add: +
Subtract: -
Multiply: *
Divide: /
These all work how you might guess:

console.log(3 + 4); // Equals 7
console.log(5 - 1); // Equals 4
console.log(4 * 2); // Equals 8
console.log(9 / 3); // Equals 3

- For example, every string instance has a property called length that stores the number of characters in it. You can retrieve property information by appending the string with a period and the property name:

- console.log('Hello'.length);
In the example above, the value saved to the length property is retrieved from the string, 'Hello'. The program prints 5 to the console, because Hello has five characters in it.
On the first line, the .toUpperCase() method is called on the string instance 'Hello'. The result is logged to the console. This method returns a string in all capital letters: 'HELLO'.
On the second line, the .startsWith() method is called on the string instance "Hey". This method also accepts the character 'H' as an input between the opening and closing parentheses. Since the string 'Hey' does start with the letter 'H', the method returns the boolean true.
- If you wish to get rid of whitespace, use the .trim method.
- If you want to use method without an instance, javascript libraries will be needed. 
- Four essential data types in JavaScript include strings, numbers, booleans, and null.
- Data is printed, or logged, to the console with console.log().
- Four built-in mathematical operators include +, -, *, and /.
- JavaScript associates certain properties with different data types.
- JavaScript has built-in methods for different data types.
- Libraries are collections of methods that can be called without an instance.
- You can write single-line comments with // and multi-line comments between /* and */.
- const, short for constant, is a JavaScript keyword that creates a new variable with a value that cannot change.
myName is the variable's name. Notice that the word has no spaces, and we capitalized the N. Capitalizing in this way is a standard convention in JavaScript called camelCasing, because the capital letters look like the humps on a camel's back.
= is the assignment operator. It assigns the value ('Arya') to the variable (myName).
'Arya' is the value assigned (=) to the variable myName.
-After the variable is declared, we can print 'Arya' to the console with: console.log(myName).
- The first three operators (+=, -=, and *=) perform the mathematical operation of the first operator (+, -, or *) using the number on the right, then assign the new value to the variable.
- The last two operators are the increment (++) and decrement (--) operators. These operators are responsible for increasing and decreasing a number variable by one, respectively.
- The + operator, known until now as the addition operator, is used to interpolate (insert) a string variable into a string, as follows:
- Instead of using quotes around the string, use backticks (this key is usually located on the top of your keyboard, left of the 1 key).
- Wrap your variable with ${myVariable}, followed by a sentence. No +s necessary.
Review: Variables hold reusable data in a program.
JavaScript will throw an error if you try to reassign const variables.
You can reassign variables that you create with the let keyword.
Unset variables store the primitive data type undefined.
Mathematical assignment operators make it easy to calculate a new value and assign it to the same variable.
The + operator is used to interpolate (combine) multiple strings.
In JavaScript ES6, backticks (`) and ${} are used to interpolate values into a string.





