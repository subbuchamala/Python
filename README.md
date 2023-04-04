1  Installation
Download from: https://www.python.org/downloads/
To Check python installed in your machine, go to cmd prompt and type
python --version
IDLE tool come with Python interpretor itself. vs code, Jupyter Notebook.
2  Variable declaration Rules:
A variable name must start with a letter or the underscore character
A variable name cannot start with a number
A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
A variable name should not contain white spaces & special symbols except underscore
Variable names are case-sensitive (age, Age and AGE are three different variables)
2.1  Keywords:
Keywords are the reserved words
Examples: int, float, char, str, if, while , for

2.2  Python Datatypes / Variables:
Text Type: str
Numeric Types: int, float, complex
Sequence Types: list, tuple, range
Mapping Type: dict
Set Types: set, frozenset
Boolean Type: bool
Binary Types: bytes, bytearray, memoryview
None Type: NoneType
4  Basic arithmetic calculations, IF-ELSE, Functions
Read input from User
User I/P - type conversion
Swapping numbers
Integer Division, Float Division
if-elif-else Statements
Functions
5  Operators
5.1  Python Comparison Operators
Operator Name Example
'==' Equal x == y
'!=' Not equal x != y
'>' Greater than x > y
'<' Less than x < y
'>=' Greater than or equal to x >= y
'<=' Less than or equal to x <= y
5.2  Python Logical Operators
Operator Description Example Try it

'and' --Returns True if both statements are true. x < 5 and x < 10
'or' --Returns True if one of the statements is true. x < 5 or x < 4
'not' --Reverse the result, returns False if the result is true
5.3  Python Membership Operators
Operator Description Example

'in' --Returns True if a sequence with the specified value is present in the object. x in y
'not in' --Returns True if a sequence with the specified value is not present in the object. x not in y
5.4  Python Bitwise Operators
Operator Name Description

& --->AND Sets each bit to 1 if both bits are 1
| --->OR Sets each bit to 1 if one of two bits is 1
^ --->XOR Sets each bit to 1 if only one of two bits is 1
~ --->NOT Inverts all the bits
<< --->Zero fill left shift. Shift left by pushing zeros in from the right and let the leftmost bits fall off
'>>' --->Signed right shift. Shift right by pushing copies of the leftmost bit in from the left, and let the rightmost bits fall off
6  Loops
6.1  The while Loop
With the while loop we can execute a set of statements as long as a condition is true.
6.2  Python range() Loop
The range() function returns a sequence of numbers,
Starting from 0 by default, and increments by 1 (by default), and ends at a specified number.
6.3  Python For Loop
A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).
7  Strings & string methods
8  Python Collections (Arrays)¶
There are four collection data types in the Python programming language:

List ----------is a collection which is ordered and changeable. Allows duplicate members.
Tuple -------is a collection which is ordered and unchangeable. Allows duplicate members.
Set ----------is a collection which is unordered, unchangeable, and unindexed. No duplicate members.
Dictionary --is a collection which is ordered and changeable. No duplicate members.
Set items are unchangeable, but you can remove and/or add items whenever you like.
As of Python version 3.7, dictionaries are ordered. In Python 3.6 and earlier, dictionaries are unordered.
9.1  Access List Items¶
List items are indexed and you can access them by referring to the index number.
Note: The first item has index 0.
Negative Indexing
Negative indexing means start from the end
-1 refers to the last item, -2 refers to the second last item etc.
Range of Indexes
You can specify a range of indexes by specifying where to start and where to end the range.
When specifying a range, the return value will be a new list with the specified items.
Note: The search will start at index 2 (included) and end at index 5 (not included).
10  tuples¶
Tuples are used to store multiple items in a single variable. A tuple is a collection which is ordered and unchangeable.

Tuple:
Ordered.
Unchangeable/immutable.
Allows duplicate members.
Method Description
count() ---Returns the number of times a specified value occurs in a tuple
index() ---Searches the tuple for a specified value and returns the position of where it was found
11  sets
A set is a collection which is unordered, unchangeable*, and unindexed.
set:
unordered,
unchangeable, (* Note: Once a set is created, you cannot change its items, but you can remove items and add new items.)
unindexed.
No duplicate members.
12  dictionaries
Dictionaries are used to store data values in key:value pairs.
Dictionary --is a collection which is ordered and changeable. No duplicate members.
Dictionary:
Ordered
Changeable
No duplicate members
