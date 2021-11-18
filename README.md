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
manipulate variables. A variable is a name that refers to a value. An assignment statement creates new variables and gives them values:

>>> message = 'And now for something completely different'

>>> n = 17

>>> pi = 3.1415926535897931

This example makes three assignments.

The first assigns a string to a new variable
named message; the second assigns the integer 17 to n; the third assigns the
(approximate) value of π to pi.


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


# Variable names and keywords

Programmers generally choose names for their variables that are meaningful and
document what the variable is used for.

Variable names can be arbitrarily long. They can contain both letters and numbers,
but they cannot start with a number. 
It is legal to use uppercase letters, but it is a good idea to begin variable names with a lowercase letter.
The underscore character ( _ ) can appear in a name. It is often used in names with
multiple words, such as my_name or airspeed_of_unladen_swallow. Variable names can start with an underscore character, but we generally avoid doing this unless we are writing library code for others to use.


If you give a variable an illegal name, you get a syntax error:

>>> 76trombones = 'big parade'

SyntaxError: invalid syntax

>>> more@ = 1000000

SyntaxError: invalid syntax

>>> class = 'Advanced Theoretical Zymurgy'

SyntaxError: invalid syntax

76trombones is illegal because it begins with a number. 
more@ is illegal because it contains an illegal character, @. But what’s wrong with class?

It turns out that class is one of Python’s keywords. The interpreter uses keywords
to recognize the structure of the program, and they cannot be used as variable
names.

Python reserves 35 keywords:

and del from None True
as elif global nonlocal try
assert else if not while
break except import or with
class False in pass yield
continue finally is raise async
def for lambda return await

# Statements
A statement is a unit of code that the Python interpreter can execute. We have
seen two kinds of statements: print being an expression statement and assignment.
When you type a statement in interactive mode, the interpreter executes it and
displays the result, if there is one.

A script usually contains a sequence of statements. If there is more than one
statement, the results appear one at a time as the statements execute.

For example, the script

>>>print(1)

>>>x = 2

>>>print(x)

produces the output

1
2

The assignment statement produces no output.
