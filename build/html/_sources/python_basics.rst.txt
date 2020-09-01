
==========================
Welcome to Python Basics
===========================

Learn Python Basics 
---------------------

Simple Operations
=====================

print('spam and eggs')

Python code often contains references to the comedy group Monty Python. This is why the words, "spam" and "eggs" are often used as placeholder variables in Python where "foo" and "bar" would be used in other programming languages.


print(2 + 2)
print(5 + 4 - 3)

The spaces around the plus and minus signs here are optional (the code would work without them), but they make it easier to read.


Simple Operations
******************

Python also carries out multiplication and division, using an asterisk * to indicate multiplication and a forward slash / to indicate division.

Use parentheses to determine which operations are performed first.
print( 2 * (3 + 4) )
print( 10 / 2 )

Using a single slash to divide numbers produces a decimal (or float, as it is called in programming). We'll have more about floats in a later lesson.


Simple Operations
******************

Dividing by zero in Python produces an error, as no answer can be calculated.

print(11 / 0)

Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ZeroDivisionError: division by zero

In Python, the last line of an error message indicates the error's type.
Read error messages carefully, as they often tell you how to fix a program!

Floats
=======
As you saw previously, dividing any two integers produces a float.
A float is also produced by running an operation on two floats, or on a float and an integer.
print( 8 / 2 )

print( 6 * 7.0 )

print( 4 + 1.65 )
Try It Yourself


A float can be added to an integer, because Python silently converts the integer to a float.

