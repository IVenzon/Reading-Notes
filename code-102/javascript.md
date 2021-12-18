# Javascript:

Javascript is a lightweight/interpreted/just-in-time compiled programming language that has first-class functions. It is used in a variety of things, but it is most known as the scripting language for webpages. It is prototype-based, and supports a range of programming styles. Javascript runs client-side, which means it can be used to program the behavior of webpage elements in response to an event, such as a mouse click.

## Input/Output in Javascript:

There are several things that define an 'input', such as mouse clicks and typing.

In Javascript, we can use functions to retrieve the content from the input fields and assign these values to variables. We can then use these variables to create an HTML snippet and assign it to a new variable.

This new variable can then be used to 'output' something on our page.

## Javascript Variables:

In Javascript, variables are containers for storing data/values.

We can declare a variable in Javascript in 3 ways: 'var', 'let', and 'const'. Let us look at 'var' for now. For example:

> var x = 7;

> var y = 2;

> var z = x + y;

In this case, the variable 'x' stores the value 7, the variable 'y' stores the value 2, and the variable 'z' stores the value 9. Note in the third line how we can use variables in expressions in a similar way to algebra.

All Javascript variables must have unique names, which are called **identifiers**. In the variables above, the identifiers are 'x', 'y', and 'z' respectively, but identifiers can be much more descriptive. The general rules for making an identifier are as follows:

- Names can contain letters, digits, underscores, and dollar signs
- Names **must** begin with a letter
- Names can begin with _ or $
- Names are case sensitive. If you have var y and var Y, they are treated as two distinct variables
- Reserved words, such as JS keywords, cannot be used as names.

A different case arises when we declare a variable but don't assign it a value. For example:

> var whatsthis;

In this case, 'whatsthis' has the value *undefined*.

## The Assignment Operator:

One important distinction to make in Javascript is the assignment operator (=) vs. the equals operator (==).

If we want to assign a value to variable, we need to use the assignment operator = (only one equals sign). For instance:

> x = x + 1;

This statement first calculates the value of x + 1, then assigns that value to x. In other words, this statement increments the value of x by one each time it runs.

On the other hand, if we wanted to check if a variable equaled some value, then we would need to use the equals operator (two equals signs). Note that this is a **VERY** common source of error, so if a problem arises and you get stuck, be sure to check how many equals signs you used!