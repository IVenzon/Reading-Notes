# Programming with Javascript:

## Control Flow:

The control flow is the order in which the computer executes statements in a script.

In the case of Javascript (and many other languages), code is read from top to bottom.

In order to dictate the order of execution for our code, we need to utilize control structures, such as conditonals, loops, and functions, or dictate certain actions to occur based on events, such as a mouse click.

For example, take the following conditional:

If we tie the execution of this conditional to a button press, we can see that if the input box is empty, the conditional will call the function that prompts the user to complete the form. If the form is not empty, then clicking the button will submit the form as intended. This is just a simple set of code, but we can already see how it drastically changes the order in which the entire program is executed.

## Javascript Functions:

In Javascript, a function is a block of code which is designed to perform a specific task. Functions are executed when they are 'called' within the program.

The structure of a function is as follows. First we define a function with the 'function' keyword. We then follow with the function name, and finally a set of parentheses (). The rules for naming a function are the same as for naming a variable.

The parameters of the function are what lie within the parenthesis. A function can have multiple parameters, each separated by a comma.

The code to be executed by the function then lies within the curly brackets {}.

When you call a function that has parameters, function 'arguments' are the 'values' received by the function. When these values go inside the function, they are treated as local variables.

If you function includes a 'return' statement, when your function reaches that return statement, the function will end. The function will then compute a 'return value', which is sent back to the caller. For example, if you have a function getNum that returns a random number, such as:

> var myNum = getNum();

Then the function 'getNum' will return that number to the variable 'myNum', and the value of myNum will be that number.

Functions are incredibly useful because they let us reuse code. Instead of writing the same block of code over and over again, we can just write that block of code once in a function then call the function whenever we need to use it. Functions also let us use the same block of code repeatedly but with different arguments, which lets us produce a multitude of results.

## Javascript Operators:

In Javascript, there are a variety of operators, some pertaining to numbers, some pertaining to strings, and some that can use both.

One of the most important operators is the assignment operator (=). This assigns a value to a variable. For instance, if I wanted a variable with the value 7, I would write:

> var iWant7 = 7;

There are also a list of operators pertaining to numbers that allow us to do calculations. These are called the **arithmetic operators**.

- (+): Addition
- (-): Subtraction
- (*): Multiplication
- (**): Exponentiation
- (/): Division
- (%): Modululs (Gives the remainder of a division. For example, 5%2 gives the value 1.)
- (++): Increment by one
- (--): Decrement by one

When it comes to strings, the (+) operator is used to concatenate (combine) strings. For instance, if I had two variables firstName = "Ian" and lastName = "Venzon"

> var fullName = firstName + " " + lastName;

The var fullName will have the value "Ian Venzon".

We can also add strings and numbers using the same method. If I add the firstName variable to the number 9, I get:

> var addResult = firstname + 9

the var addResult will have the value "Ian9".

Note that when you concatenate a string and a number, **the result will return a string!**

There are also operators that deal with comparing values to eachother. These are called teh **comparison operators**.

- (==): Checks to see if two values are equal to eachother
- (!=): Checks to see if two values are not equal to eachother
- (>): Checks to see if the first value is greater than the second
- (<): Checks to see if the first value is less than the second
- (>=): Checks to see if teh first value is greater than or equal to the second
- (<=): Checks to see if teh first value is less than or equal to the second