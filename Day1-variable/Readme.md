
# syntax of python and variables

## print syntax
print('hello world') 

## python indentation
Indentation refers to the spaces at the beginning of a code line.
  ````bash
  if 3 > 2:
    print("Three is greater than two!") 
  ````
 Python will give you an error if you skip the indentation.
 ````bash
if 5 > 2:
print("Five is greater than two!")
````
## Comment
Comments can be placed at the end of a line, and Python will ignore the rest of the line.
````bash
print("Hello, World!") #This is a comment
````
### Multiline comment
```bash
"""
This is a comment
written in
more than just one line
"""
print("Hello, World!")
````
# Variable

A variable is created the moment you first assign a value to it.
````bash
x = 2
y = "sniper"
print(x)
print(y)
````
### Casting
If you want to specify the data type of a variable, this can be done with casting.
````bash
x = str(3)    # x will be '3'
y = int(3)    # y will be 3
z = float(3)  # z will be 3.0
````
### Type
You can get the data type of a variable with the type() function.
````bash
x = 3
y = "sniper"
print(type(x))
print(type(y))
````
### case sensitive
```bash
a = 4
A = "Sally"
#A will not overwrite a
````
### variable name

- A variable name must start with a letter or the underscore character
- A variable name cannot start with a number
- A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- Variable names are case-sensitive (age, Age and AGE are three different variables)
### Legal variable name
````bash
myvar = "sniper"
my_var = "test"
_my_var = "geek"
myVar = "John"
MYVAR = "alex"
myvar2 = "John"
````
### Illegal variable 
````bash
2myvar = "test"
my-var = "John"
my var = "geek"
````
### multi word variable

#### camel case
````bash
myVariableName = "John"
````
#### pascle case
````bash
MyVariableName = "John"
````
#### snake case
````bash
my_variable_name = "John"
````
### global variable

Variables that are created outside of a function (as in all of the examples above) are known as global variables.
````bash
x = "awesome"

def myfunc():
  print("Python is " + x)

myfunc()
````
If you create a variable with the same name inside a function, this variable will be local, and can only be used inside the function. The global variable with the same name will remain as it was, global and with the original value.

```bash
x = "awesome"

def myfunc():
  x = "fantastic"
  print("Python is " + x)

myfunc()

print("Python is " + x)
````
### user input
name = input('enter the username')









