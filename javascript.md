# Javascript

## What is Javascript?

Javascript is a programming language that is primarily known for programming web pages. Anytime that a webpage is more than just a static page it's probably because of Javscript; it adds a layer of interactivity to web pages. Take a button for example. With HTML it is possible to put text in the button, and with CSS it is possible to style it to look like a button. Javscript would allow one to click the button.

## Javscript Expressions and Operators

Javscript has many operators which are used to create programs. Common operators are assignment operators, which assign a value to a variable. The following is a table of common assignment operators:

Name | Operator
-----|----------
Assignment | x = y
Addition Assignment | x += y
Subtraction Assignment | x -= y
Multiplication Assignment | x *= y
Divions Assignment | x /= y
Remainder Assignment | x %= y

In addition to assignment operators there are also comparison operators. These operators compare two values and return a result based on the comparison. The following is a table of common comparison operators:

Name | Description
-----|------------
Equal (==) | Returns true if operands are equal
Not Equal (!=) | Returns true if operands are not equal
Strict Equal (===) | Returns true if the value of the operands are equal
Strict Not Equal (!==) | Returns true if the value of the operands is not equal
Greater Than (>) | Returns true if the if left operand is greater than the right operand
Greater Than or equal (>=) | Returns true if the left operand is greater than or equal to the right operand
Less Than (>) | Returns true if the if left operand is less than the right operand
Less Than or equal (<=>) | Returns true if the left operand is less than or equal to the right operand

## Javascript Functions

A function is a basic building block of a Javascript program. An example of a function is as follows:

> `function square(number) {return number * number;}`

A function declaration must consist of the function keyword and the following three things:

* The name of the function
* Parameters, enclosed in parentheses
* Javascript statements that define the function, enclosed in curly braces

In the function example above the name of the function is `square`, the parameter is `number` and the Javascript statement is `{return number * number;}`.

To call the above function one would type the following:

> `square(5)`