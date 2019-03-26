# Writing clean code based on PEP8 guidelines

Clear and well-written code is important. The main set of conventions for Python, written by Guido Van Rossum, is called [PEP8](https://www.python.org/dev/peps/pep-0008/#prescriptive-naming-conventions).

For our course, remember the following:

__1. Maximum line length__
* Lines of code shouldn't exceed 79 characters.
* To comply with this, break code into several lines by wrapping expressions in parentheses.

__2. Imports__
* Import libraries at the top of your notebook. Use a new line for each import.
* Learn the conventional shortened names for common libraries (eg. import pandas as pd).

<pre>
YES:
import sys
import os
</pre>

<pre>
NO: 
import sys, os
</pre>

__3. Declaring strings__
* Python lets you use single quotes or double quotes around strings; pick one option and stick to it.

<pre>
YES:
string1 = 'I love Python'
string2 = 'not R'
</pre>

<pre>
NO:
string1 = "I love Python"
string2 = 'not R'
</pre>

__4. Whitespace__
* Use spaces between operators
* Be consistent and don't add redundant whitespace.

<pre>
YES:
a = b + c
spam(ham[1], {eggs: 2})
</pre>

<pre>
NO:
a=b+c
spam( ham[ 1 ], { eggs: 2 } )
</pre>

__5. Comments__
* Start comments with # and a single space.

<pre>
YES:
x = x + 1          # Increment x
</pre>

__6. Naming__
* Function and variable names should be lowercase, with underscores between the words as necessary to improve readability.
* Use descriptive variable names.

YES:

mean_trip_time = []

PROBABLY NOT:

mtt = []

