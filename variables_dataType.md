[Home](https://github.com/subithou/Python) / Variables and Data Types
# Varibales and Data Types

### What is a variable?
* The variable is a named memory location which can store the data.
* Variable names are case sensitive ( num and NUM are considered as different variables ).   

 **Rules for creating a variable name** 
  * Name can be formed by using numbers, alphabets and underscore ( _ ). 
  * First letter should be an alphabet or underscore ( _ ).
  * The special characters are not allowed, except underscore ( _ ).
  * Keywords are not allowed.
  * Blank spaces are not allowed.
    
``` text
Example

Valid variable names :  

  * variable1
  * _num
  * p123
  
Invalid variable names :

  * 7name - The starting letter should be an alphabet
  * vari%#@!able - The special characters are not allowed
  * if - Keywords are not allowed
  * Sachin Tendulkar - Blank spaces are not allowed
```


```python
Python code
-----------

a = 10 # 'a' is a variable which stores the integer number 
variable1 = 26.59 #'variable1' is a variable which stores the floating point number
name = "Python" #'name' is a variable which stores the string.
```
### Good to know
* In python we have no need to specify the data type of the variable at the time of variable creation.
* The variable creation is also known as _variable declaration_. In Python no need of variable declaration .  
* Assign the values in to variable is known as _variable initialisation_.
* In Python only the variable initialisation is needed, The Python automatically understand which type of data we stored in that variable.
* Assignment operator ( = ) is used to assign the values or data in to variable.
* print() function is used to display the content.

```python
Python code
-----------
a = 10 #The variable 'a' which stores integer number 10.
b = -35.6 #The varibale 'b' which stores floating point number -35.6
name = "Python" #The variable 'name' which stores string.

print(a) #Display the content in 'a'.
print(b) #Display the content in 'b'.
print(name) #Display the content in 'name'.

Output
------
10
-35.6
Python
```
### Data Types
* The Data Type means it's the type of data we use.  
* In mathematics we can see decimal numbers, natural numbers, complex number ...etc, like this every programming languages have different data types.  
* In Python the data types care 
  * Numeric Types -   `str`
  * Text Type -       [`int`](#Integer)<a></a> [`float`](#Floating_point_Number)<a></a> [`complex`
 ](#Complex_Number)<a></a>
  * Sequence Types -  `list` `tuple` `range`
  * Mapping Type -    `dict`
  * Set Types -       `set` `frozenset`
  * Boolean Type -    `bool`
  * Binary Types -    `bytes` `bytearray` `memoryview`

## Numeric Types
In Numeric Data Types contains 
* [Integers](#Integer)<a name="Integer"></a>
* [Floating point Number](#Floating_point_Number)<a name="Floating_point_Number"></a>
* [Complex Number](#Complex_Number)<a name="Complex_Number"></a>

### Integer 
* Int or Integer which can be a whole numbers, positive and negative numbers.
* It doesn't contain decimals.  
Example
```python
Python code

a = 10
b = -20
c = 56987

print(type(a))
print(type(b))
print(type(c))

Output 
<class 'int'>
<class 'int'>
<class 'int'>
```

### Floating point Number
* Float or Floating point Number whih can be positive and negative numbers with decimals.
* Also it can be represent using **e** or **E**, which indicate the power of 10.
```
Example for Floating point number :

10.56
20.15
-53.069875
25e3
-5632e4
```

### Complex Number
* Complex numbers are in the form of **a + bj**
* **a** is real part,**bj** is imaginary part and **a&b** are constants
```
Example for Complex Numbers :

10+20j
-20j
10j
```

## Text Type
### String
* String is a set of characters which is enclosed in a single quote or double quote.
* Multi line strings are represented using tripple single quote.
```text
Example for String :

'Hello world'

"My name is Python"

''' 
Name : Python
Type : Programming Language
'''
