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

- Review: Variables hold reusable data in a program.
- JavaScript will throw an error if you try to reassign const variables.
- You can reassign variables that you create with the let keyword.
- Unset variables store the primitive data type undefined.
- Mathematical assignment operators make it easy to calculate a new value and assign it to the same variable.
- The + operator is used to interpolate (combine) multiple strings.
- In JavaScript ES6, backticks (`) and ${} are used to interpolate values into a string.

- Control flow statements enable JavaScript programs to make decisions by executing code based on a condition. If a given condition is true, we execute one block of code. If the statement is false, we execute another block of code. For instance, if we were making a game in which the user had to choose which door to enter, we'd need a way for the program to know what to do once the user was in the next room.

-Lines of code between curly braces are called blocks. if/else statements have two code blocks. If the variable needsCoffee is true, the program will run the first block of code. Otherwise, it will run the other block of code.
needsCoffee is the condition we are checking inside the if's parentheses. Since it is equal to true, our program will run the code between the first opening curly brace { (line 2) and the first closing curly brace } (line 4). It will ignore the else { ... } part. In this case, we'd see Finding coffee log to the console.
If needsCoffee were false, only the console.log() statement in the else block would be executed.

- If we changed if (variableOne) to say if (variableTwo), that condition would evaluate to falsy because we have not created a variable called variableTwo in this program. In other words, variableOne is truthy and variableTwo is falsy.

- false
- 0 and -0
- "" and '' (empty strings)
- null
- undefined
- NaN (Not a Number)
- document.all (something you will rarely encounter)
- There is an important di

- JavaScript provides an operator for swapping the truthiness and falsiness of values - the exclamation point (!). We can use this in conditional statements as shorthand to check if the value of a variable evaluates to false rather than true.

- To check if two things equal each other, we write === (three = signs in a row).
To check if two things do not equal each other, we write !== (an exclamation with two = signs in a row).

- To check if two things do not equal each other, we write !== (an exclamation with two = signs in a row).

- 1. We created a variable named stopLight that is assigned to the string green.

2. Then, there's an if/else statement with multiple conditions, using else if. else if allows us to check multiple values of the stopLight variable and output different things based on its color.

3. The block ends with the singular else we have seen before. The else is a catch-all for any other situation. For instance, if the stopLight was blinking blue, the last else would catch it and return a default message.

- In English, sometimes we say "both of these things" or "either one of these things." Let's translate those phrases into JavaScript with special operators called logical operators.

To say "both must be true," we use &&.
To say "either can be true," we use ||.

- he switch keyword initiates the statement and is followed by ( ... ), which contains the condition that each case will compare to. In the example, the condition is groceryItem.
- Inside the block, { ... }, there are cases. case is like the else if part of an if/else if/else statement. The word following the first case is 'tomato'. If groceryItem equalled 'tomato', that case's console.log() would run.
groceryItem equals 'papaya', so the first and second case statements are skipped. The third case runs since the case is 'papaya', which matches groceryItem's value. This particular program will log Papayas are $1.29.
- Then the program stops with the break keyword. This keyword will prevent the switch statement from executing any more of its code. Without adding break at the end of each case, the program will execute the code for all matching cases and the default code as well. - -- This behavior is different from if/else conditional statements which execute only one block of code.
- At the end of each switch statement, there is a default condition. If none of the cases are true, then this code will run.
