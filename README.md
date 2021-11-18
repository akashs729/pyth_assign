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

Not surprisingly, strings belong to the type str and integers belong to the type
int. Numbers with a decimal point belong to a type called float,
because these numbers are represented in a format called floating point.
>>> type(3.2)
<class 'float'>

What about values like “17” and “3.2”? They look like numbers, but they are in
quotation marks like strings.
