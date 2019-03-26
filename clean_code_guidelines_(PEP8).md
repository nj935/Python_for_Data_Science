# Writing clean code based on PEP8 guidelines

Clear and well-written code is important. The main set of conventions for Python, written by Guido Van Rossum, is called PEP8.

For our course, remember the following:

1. Maximum line length
* Lines of code shouldn't exceed 79 characters.
* To comply with this, break code into several lines by wrapping expressions in parentheses (example here).

3. Imports
* Import libraries at the top of your notebook. Use a new line for each import.
* Learn the conventional shortened names for common libraries (eg. import pandas as pd).

YES:
import sys
import os

NO: 
import sys, os

4. Declaring strings
* Python lets you use single quotes or double quotes around strings; pick one option and stick to it.

YES:
string1 = 'I love Python'
string2 = 'not R'

NO:
string1 = "I love Python"
string2 = 'not R'

5. Whitespace
* Use spaces between operators
* Be consistent and don't add redundant whitespace.

YES:
a = b + c
spam(ham[1], {eggs: 2})

NO:
a=b+c
spam( ham[ 1 ], { eggs: 2 } )

6. Comments
* Start comments with # and a single space.

YES:
x = x + 1                 # Increment x

7. Naming
* Function and variable names should be lowercase, with underscores between the words as necessary to improve readability.
* Use descriptive variable names.

YES:
mean_trip_time = []

NO:
mtt = []

