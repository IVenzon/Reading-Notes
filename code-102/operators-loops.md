# Operators and Loops:

## Expressions and Operators:

Javascript has both binary and unary operators. A binary operator requires two operands, while a unary operator only needs one. For example:

Binary operator: operand operator operand

> 3 + 4 or x*y

Unary operator: operator operand or operand operator

> x++ or ++x

There are several types of operators in Javascript, some related to numbers, some to strings, and some that can use both.

### Assignment Operators:

The **assignment operators** assign a value to their left operands based on the value of their right operands.

The most basic assignment operator is simply known as the assignment operator (=), but there are several more that augment it with additional functionality, such as the addition assignment (+=) and multiplication assignment (*=).

If assignment operators are chained without parenthesis, then the assignment operators are grouped from **right to left**, but they are evaluated from **left to right**. For example, take:

> y = x = g()

This is equivalent to the following:

> y = (x = f())

In general, it is good practice to avoid chaining assignment operators, as it could lead to unintended behavior.

### Comparison Operators:

The **comparison operators** compare their operands and then return a logical value (true/false) based on whether the comparison was true. 

If two different data types are compared, then Javascript will try to convert them in order to give a comparison. To avoid this behavior, use the (===) and/or (!==) operators, as they check if both the value and the data type are the same.

### Arithmetic Operators:

The **arithmetic operators** take numerical values as their operands and return a single numerical value as their result.

The standard arithmetic operators are:

1. Addition (+)
2. Subtraction (-)
3. Multiplication (*)
4. Division (/)

### Logical Operators:

The **locigal operators** are typically used with boolean values, and when they are they also return a boolean value.

The Logical **AND** (&&) is used if we need both expressions of a conditional to be true. For example:

> if (x && y) 

This will only run if x is true and y is true. If either are false or both are false, then it will not run.

The Logical **OR** (\|\|) is used if we only need one expression of a conditional to be true. For example:

> if (x || y)

This will run if x is true, y is true, or both are true. If both are false, then it will not run.

The Logical **NOT** (!) is used if we want to check that something is not true. For example:

> if (!x)

This will only run if x is false. If x is true, then it will not run.

For a complete list of all the types of operators, click [here!](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

## Loops and Iteration:

In Javascript, loops give us an easy way to do something repeatedly. There are several ways to start a loop, each with their own distinct start/end points. Based on your situation, some loops may be more favorable than others.

### for loops:

A **for loop** repeats until a specified condition returns false. For example:

> for (let i = 0; i < 10; i++)

This loop will iterate a total of 10 times. It will loop when i = 0, 1, 2, 3, 4, 5, 6, 7, 8, and 9. When i is incremented to 10, then the second condition is false, and the loop will break.

### while loops:

A **while loop** will repeat as long as the specified condition returns true. For example:

> while (x < 10) {x++;}

This loop will also iterate a total of 10 times. It will loop when x = 0, 1, 2, 3, 4, 5, 6, 7, 8, and 9. When x is incremented to 10, the condition is false, and the loop will break.

### The break/continue statement:

If you want to terminate a loop, use the **break** statement. Using it without a label will terminate the loop immediately, while if it used with a label, it will terminate the specified labeled statement.

If you want to restart a while/for loop, use the **continue** statement. Using it without a label will terminate the current iteration of the loop and continue the loop at the next iteration. Note that this does not result in the termination of the loop, just that specific iteration. If it is used with a label, it applies to the looping statement identified with that label.

For a complete list of all the types of loops, click [here!](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)