
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
````bash
a = "Hello, World!"
print(a[1])
````
#### looping through a string
````bash
for x in "banana":
  print(x)
````
#### string length
````bash
a = "Hello, World!"
print(len(a))
````
#### check strings
````bash
txt = "The best things in life are free!"
print("free" in txt)
````
#### check if not
````bash
txt = "The best things in life are free!"
print("expensive" not in txt)
````



























