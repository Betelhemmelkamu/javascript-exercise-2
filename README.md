//array methods https://www.w3schools.com/js/js_array_methods.asp
Array Methods: Array methods are functions that operate on arrays, which are collections of data. They allow you to modify, manipulate, and extract data from arrays.

Purpose of Array Methods: Array methods serve various purposes, including:

Adding and Removing Elements: Methods like push() and pop() add and remove elements from the end of an array, respectively. Methods like shift() and unshift() add and remove elements from the beginning of an array.

Modifying Elements: Methods like slice() and splice() allow you to modify elements within an array. slice() extracts a portion of the array, while splice() modifies the array itself.

Concatenating Arrays: Methods like concat() allow you to combine multiple arrays into a single array.

Searching and Sorting: Methods like indexOf() and lastIndexOf() search for specific elements within an array, while sort() sorts the array's elements.

What are Functions?: Functions are reusable blocks of code that encapsulate a specific task or operation. They allow you to modularize your code, making it more organized, maintainable, and reusable.

// functions https://www.w3schools.com/js/js_functions.asp and https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions

Defining Functions: Functions are defined using the function keyword followed by the function name, parameter list (if any), and the function body enclosed in curly braces ({}).

Calling Functions: Functions are called using their name followed by parentheses containing any arguments or parameters passed to the function.

Function Parameters: Parameters are values passed to a function when it's called. They allow you to customize the function's behavior based on the provided data.

Function Return Values: Functions can return values using the return statement. The returned value is the result of the function's execution.

Function Scope: Function scope determines the visibility of variables within a function. Local variables are only accessible within the function, while global variables are accessible throughout the program.

Function Types: JavaScript supports various function types, including:

Regular Functions: The most common type, used for performing specific tasks.
Arrow Functions: A concise syntax for defining functions, especially with single expressions.
Generator Functions: Generate a sequence of values over time.
Recursive Functions: Call themselves to solve problems involving self-similarity.
Defining and Calling Functions:

Function declarations: Defining functions using the function keyword, followed by the function name, parameter list, and function body.

Function expressions: Creating functions using function expressions, which are part of an expression rather than a separate statement.

Function calls: Invoking functions by specifying their name along with any arguments passed within parentheses.

Function Parameters and Return Values:

Function parameters: Specifying values that are passed to a function when it's called, allowing for dynamic behavior.

Function return values: Returning values from a function using the return statement, providing the outcome of the function's execution.

Function Scope and Lifetime:

Function scope: Defining the visibility of variables within a function, with local variables accessible only within the function and global variables accessible throughout the program.

Function lifetime: Understanding how functions are created, stored, and executed, influencing their persistence in memory.

Function Types and Variations:

Regular functions: The most common type, used for performing specific tasks and manipulating data.

Arrow functions: Concise syntax for defining functions, particularly for single expressions.

Generator functions: Creating functions that can yield multiple values over time, allowing for asynchronous operations.

Recursive functions: Calling themselves repeatedly to solve problems involving self-similarity.

Function Properties and Methods:

Function properties: Accessing information about a function, such as its name, length, and whether it's an arrow function.

Function methods: Calling methods associated with a function, such as apply(), call(), and toString(), for varying purposes.

Function Optimizations and Techniques:

Memoization: Memoizing functions to store results for repeated calls, improving performance.

Currying: Currying functions to break them down into smaller functions, making them more modular and reusable.

Closures: Creating closures to capture the context of a function, enabling access to its lexical scope.

// control flow https://www.javascripthelp.org/learn/basics/control-flow-statements/

Conditional Statements:

Conditional statements evaluate expressions to determine whether specific conditions are met. Based on the outcome of the evaluation, these statements determine the path of execution.

if-else Statement: The if-else statement is the most basic conditional statement. It checks a condition and executes the corresponding block of code if the condition is true, or the alternative block if the condition is false.
If the condition is true, the code within the if block is executed.

If the condition is false, the code within the else block is executed.

switch Statement: The switch statement is used for multiple-way branching. It evaluates an expression and executes the corresponding case block based on the expression's value.
The expression is evaluated, and each case block is checked against its value.

If the expression matches the value of a case block, the code within that block is executed.

The break statement is optional but recommended to prevent the execution of subsequent case blocks.

If the expression does not match any case values, the code within the optional default block is executed.

Loop Statements:

Loop statements repeat a block of code multiple times until a specific condition is met.

for Loop: The for loop iterates a specified number of times.
It initializes a variable, checks a condition, and updates the variable after each iteration.

The for loop is particularly useful for iterating over a sequence of numbers or data.

while Loop: The while loop iterates as long as a specified condition is true.
It repeatedly executes the code block until the condition evaluates to false.

The while loop is useful for situations where the number of iterations is not known beforehand.

do-while Loop: The do-while loop executes the code block once, before checking the condition.
It then continues to iterate as long as the condition is true.

The do-while loop ensures that the code block is always executed at least once, even if the condition is initially false.
