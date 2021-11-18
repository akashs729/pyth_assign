# Values and types

Values and types

A value is one of the basic things a program works with, like a letter or a number. 
These values belong to different types: 2 is an integer, and “Hello, World!” is a
string, so called because it contains a “string” of letters. You (and the interpreter)
can identify strings because they are enclosed in quotation marks.

If you are not sure what type a value has, the interpreter can tell you.
>>> type('Hello, World!')

<class 'str'>

>>> type(17)

<class 'int'>

Strings belong to the type str and integers belong to the type
int. Numbers with a decimal point belong to a type called float,
because these numbers are represented in a format called floating point.
>>> type(3.2)

<class 'float'>

Values like “17” and “3.2”? They look like numbers, but they are in
quotation marks like strings.

>>> type('17')

<class 'str'>

>>> type('3.2')

<class 'str'>

They’re strings.

# Variables

One of the most powerful features of a programming language is the ability to
manipulate variables. A variable is a name that refers to a value.
An assignment statement creates new variables and gives them values:

>>> message = 'And now for something completely different'
>>> n = 17
>>> pi = 3.1415926535897931

This example makes three assignments.

The first assigns a string to a new variable
named message; the second assigns the integer 17 to n; the third assigns the
(approximate) value of  to pi.
To display the value of a variable, you can use a print statement:
>>> print(n)
17
>>> print(pi)
3.141592653589793
The type of a variable is the type of the value it refers to.
>>> type(message)
<class 'str'>
>>> type(n)
<class 'int'>
>>> type(pi)
<class 'float'>
