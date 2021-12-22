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

The Logical **OR** (||) is used if we only need one expression of a conditional to be true. For example:

> if (x || y)

This will run if x is true, y is true, or both are true. If both are false, then it will not run.

The Logical **NOT** (!) is used if we want to check that something is not true. For example:

> if (!x)

This will only run if x is false. If x is true, then it will not run.

For a complete list of all the types of operators, click [here!](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)