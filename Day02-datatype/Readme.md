
# python Datatype & string manipulation

## built-in-datatype
Variables can store data of different types, and different types can do different things.

Python has the following data types built-in by default, in these categories:
- Text Type:	````str````
- Numeric Types:	````int````, ````float````, ````complex````
- Sequence Types:	````list````, ````tuple````, ````range````
- Mapping Type:	````dict````
- Set Types:	````set````, ````frozenset````
- Boolean Type:	````bool````
- Binary Types:	````bytes````, ````bytearray````, ````memoryview````

## Setting the Data Type
In Python, the data type is set when you assign a value to a variable:

| Example	| Data Type	|
| ----------------- | ----------- |
 x = "Hello World"	| str	|
 x = 20	| int	
 x = 20.5 | float	
 x = 1j	| complex	
 x = ["apple", "banana", "cherry"] |	list	
 x = ("apple", "banana", "cherry")	| tuple	
 x = range(6)	| range	
 x = {"name" : "John", "age" : 36}	| dict	
 x = {"apple", "banana", "cherry"}	| set	
 x = frozenset({"apple", "banana", "cherry"}) | frozenset	
 x = True	| bool	
 x = b"Hello"	| bytes	
 x = bytearray(5)	| bytearray	
 x = memoryview(bytes(5))	| memoryview


## Setting the Specific Data Type
If you want to specify the data type, you can use the following constructor functions:

|Example	| Data Type 
| ------------------------ | ---------|
x = str("Hello World")	| str	
x = int(20)	| int	
x = float(20.5)	| float	
x = complex(1j)	| complex	
x = list(("apple", "banana", "cherry"))	| list	
x = tuple(("apple", "banana", "cherry"))	| tuple	
x = range(6)	| range	
x = dict(name="John", age=36)	| dict	
x = set(("apple", "banana", "cherry"))	| set	
x = frozenset(("apple", "banana", "cherry"))	| frozenset	
x = bool(5)	| bool	
x = bytes(5)	| bytes	
x = bytearray(5)	| bytearray	
x = memoryview(bytes(5))	| memoryview

# string Manipulation

#### string
````bash
print("Hello")
print('Hello')
````
#### Assign string to a variable
Assigning a string to a variable is done with the variable name followed by an equal sign and the string:
````bash
a = "Hello"
print(a)
````
#### multiline string
You can assign a multiline string to a variable by using three quotes:
````bash
a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)
````
#### strings are arrays
Get the character at position 1 (remember that the first character has the position 0):
````bash
a = "Hello, World!"
print(a[1])
````
#### looping through a string
Since strings are arrays, we can loop through the characters in a string, with a for loop.
````bash
for x in "banana":
  print(x)
````
#### string length
To get the length of a string, use the len() function.
````bash
a = "Hello, World!"
print(len(a))
````
#### check strings
To check if a certain phrase or character is present in a string, we can use the keyword in.
````bash
txt = "The best things in life are free!"
print("free" in txt)
````
#### check if not
To check if a certain phrase or character is NOT present in a string, we can use the keyword not in.
````bash
txt = "The best things in life are free!"
print("expensive" not in txt)
````
#### slicing
Get the characters from position 2 to position 5 (not included):
````bash
b = "Hello, World!"
print(b[2:5])
````
#### slice from start
Get the characters from the start to position 5 (not included):
````bash
b = "Hello, World!"
print(b[:5])
````
#### slice to the end
Get the characters from position 2, and all the way to the end:
````bash
b = "Hello, World!"
print(b[2:])
````
#### upper case
The upper() method returns the string in upper case:
````bash
a = "Hello, World!"
print(a.upper())
````
#### lower case
The lower() method returns the string in lower case:
````bash
a = "Hello, World!"
print(a.lower())
````
#### remove wihitespace
The strip() method removes any whitespace from the beginning or the end:
````bash
a = " Hello, World! "
print(a.strip()) # returns "Hello, World!"
````
#### replace string
The replace() method replaces a string with another string:
````bash
a = "Hello, World!"
print(a.replace("H", "J"))
````
#### split string
The split() method splits the string into substrings if it finds instances of the separator:
````bash
a = "Hello, World!"
print(a.split(",")) # returns ['Hello', ' World!']
````
#### string concatenation
To concatenate, or combine, two strings you can use the + operator.
````bash
a = "Hello"
b = "World"
c = a + b
print(c)
````
#### string format
Use the format() method to insert numbers into strings:
````bash
age = 36
txt = "My name is John, and I am {}"
print(txt.format(age))
````
### string methods

| method     | description |
| --------| ---------------------------------------- |
capitalize()	| Converts the first character to upper case
casefold() |	Converts string into lower case
center() |	Returns a centered string
count()	| Returns the number of times a specified value occurs in a string
encode()	| Returns an encoded version of the string
endswith()	| Returns true if the string ends with the specified value
expandtabs()	| Sets the tab size of the string
find()	| Searches the string for a specified value and returns the position of where it was found
format()	| Formats specified values in a string
format_map()	| Formats specified values in a string
index()	| Searches the string for a specified value and returns the position of where it was found
isalnum()	| Returns True if all characters in the string are alphanumeric
isalpha()	| Returns True if all characters in the string are in the alphabet
isdecimal()	| Returns True if all characters in the string are decimals
isdigit()	| Returns True if all characters in the string are digits
isidentifier()	| Returns True if the string is an identifier
islower()	| Returns True if all characters in the string are lower case
isnumeric()	| Returns True if all characters in the string are numeric
isprintable()	| Returns True if all characters in the string are printable
isspace()	| Returns True if all characters in the string are whitespaces
istitle()	| Returns True if the string follows the rules of a title
isupper() |	Returns True if all characters in the string are upper case
join()	| Joins the elements of an iterable to the end of the string
ljust()	| Returns a left justified version of the string
lower()	| Converts a string into lower case
lstrip()	| Returns a left trim version of the string
maketrans() |	Returns a translation table to be used in translations
partition()	| Returns a tuple where the string is parted into three parts
replace()	| Returns a string where a specified value is replaced with a specified value
rfind()	| Searches the string for a specified value and returns the last position of where it was found
rindex()	| Searches the string for a specified value and returns the last position of where it was found
rjust()	| Returns a right justified version of the string
rpartition()	| Returns a tuple where the string is parted into three parts
rsplit()	| Splits the string at the specified separator, and returns a list
rstrip()	| Returns a right trim version of the string
split()	| Splits the string at the specified separator, and returns a list
splitlines()	| Splits the string at line breaks and returns a list
startswith()	| Returns true if the string starts with the specified value
strip()	| Returns a trimmed version of the string
swapcase()	| Swaps cases, lower case becomes upper case and vice versa
title()	| Converts the first character of each word to upper case
translate()	| Returns a translated string
upper()	| Converts a string into upper case
zfill()	| Fills the string with a specified number of 0 values at the beginning


















